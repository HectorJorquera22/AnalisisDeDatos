# Proyecto: Análisis y Preparación de Ventas

## Descripción
Este proyecto documenta el proceso de transformación y limpieza de datos de ventas, pasando de un formato de tabla ancha a un formato largo (tidy data) para facilitar su análisis y visualización. Además, se aplican reglas de negocio mediante técnicas de programación funcional en Python.

## Tecnologías Utilizadas
* **Python**: Lenguaje principal de procesamiento.
* **Pandas**: Utilizado para la manipulación y transformación de DataFrames.
* **Jupyter Notebooks**: Entorno de desarrollo para la experimentación y documentación del análisis.

## Proceso de Preparación de Datos
El pipeline de datos sigue los siguientes pasos críticos:

1. [cite_start]**Transformación (Melt)**: Conversión de formatos de tabla "ancho" a "largo" para normalizar los datos, facilitando su lectura por herramientas de visualización.
2. [cite_start]**Limpieza/Cálculo**: Aplicación de lógica de negocio (descuentos) utilizando *Dictionary Comprehension*, optimizando la manipulación de estructuras de datos nativas[cite: 106].
3. [cite_start]**Análisis Descriptivo**: Generación de estadísticas rápidas para evaluar la estabilidad de los datos (media, variabilidad) utilizando `df.describe()`[cite: 55].

## Instrucciones de Ejecución
1. Asegúrate de tener instalada la librería pandas: `pip install pandas`.
2. Ejecuta el notebook `analisis_ventas.ipynb` de forma secuencial.
3. Los resultados transformados se guardarán automáticamente para su uso en tableros de control (Dashboards).

## Contacto
Desarrollado para la certificación de Análisis de Datos 2026.