# AnalisisDeDatos
Portafolio con Análisis de Datos realizados

Portafolio de Proyectos de Análisis de Datos (BiciGo)

Este repositorio contiene una colección de proyectos de análisis de datos desarrollados para optimizar las operaciones y la toma de decisiones estratégicas de la empresa BiciGo, enfocándose en la **calidad del dato**, la **rentabilidad de productos** y la **expansión de negocio**.

---

## 1. Proyecto 1: Análisis de Rentabilidad y Proyección de Inventario

### Título y Descripción
**Análisis de Rentabilidad de Productos y Proyección de Inventario para Optimización de Stock.**
Este proyecto aplica el Análisis Exploratorio de Datos (EDA) para identificar los productos más rentables y evaluar tendencias estacionales, resolviendo la incertidumbre en la gestión de inventario y compras de BiciGo.

### Problema y Objetivos
* **Problema de Negocio:** Evitar la escasez de modelos de alta demanda y el exceso de stock en productos de baja rotación.
* **Objetivos del Análisis:**
    1.  Determinar el **Monto Total de Ventas** y el **Ingreso Promedio por Arriendo** por modelo.
    2.  Identificar patrones de **estacionalidad** para proyectar la demanda futura.

### Conjunto de Datos
* **Datos Utilizados:** Registros históricos de transacciones de ventas y arriendos.
* **Variables Clave:** `Modelo_Bicicleta`, `Monto_Transacción`, `Fecha`, `Tipo_Transacción`.

### Metodología y Herramientas
* **Pasos Principales:** Limpieza (post-proceso), **EDA** (Análisis Exploratorio de Datos), y creación de métricas clave.
* **Herramientas Usadas:** **Excel** (Tablas Dinámicas, Agrupación de Campos, Gráficos Dinámicos).

### Resultados y Conclusiones (Insights)
* **Hallazgo:** El modelo `MTB-Trail` y los `Servicios de Mantención Premium` contribuyen con más del 55% de los ingresos totales. La estacionalidad provoca una caída del 25-30% en arriendos durante el invierno.
* **Implicación de Negocio:** La planificación de compras y el enfoque de *stock* deben priorizar estos modelos y servicios. Se recomienda enfocar el marketing en servicios durante la temporada baja.

### Documentación Detallada
* [Detalle Completo del Proyecto 1 (Documentacion_Proyecto_Analisis_Ventas)](./Proyecto_01_Analisis_Ventas/Documentacion_Proyecto_Analisis_Ventas.docx)

---

## 2. Proyecto 2: Aseguramiento de la Calidad del Dato: Limpieza y Transformación

### Título y Descripción
**Aseguramiento de la Calidad del Dato: Estandarización y Transformación de Registros de Venta.**
Este proyecto se centró en la limpieza profunda y estandarización de los datos de transacciones, resolviendo problemas de inconsistencia y formato para garantizar que la información fuera **confiable y analizable**.

### Problema y Objetivos
* **Problema de Negocio:** Inconsistencias graves (ej. formatos mixtos, textos no estandarizados, datos combinados) que llevaban a conclusiones analíticas erróneas.
* **Objetivos del Análisis:**
    1.  Estandarizar formatos de texto (`Estado_Pago`) y corregir valores numéricos (`Monto`).
    2.  Dividir información compleja combinada (`Datos_Venta`) en campos separados (`Nombre_Cliente`, `ID_Transacción`).

### Conjunto de Datos
* **Datos Utilizados:** Archivo `Ejercicio Limpieza y transformación de datos de ventas (HECTOR JORQUERA).xlsx`.
* **Variables Clave:** `Datos_Venta`, `Monto`, `Estado_Pago`.

### Metodología y Herramientas
* **Pasos Principales:** Estandarización, Transformación, Manejo de Duplicados y Datos Faltantes, Control de Calidad.
* **Herramientas Usadas:** **Excel** (Texto en Columnas, Buscar y Reemplazar, Eliminar Duplicados, Validación de Datos).
    * *Nota: La utilización de **Texto en Columnas** fue fundamental para la división de datos complejos.* 

### Resultados y Conclusiones (Insights)
* **Hallazgo:** Se transformó una base de datos inconsistente a una versión funcional de 7 columnas analíticas, lista para cálculos.
* **Implicación de Negocio:** Eliminación del riesgo de sesgo analítico, permitiendo a la empresa confiar en sus métricas de ventas y clientes.

### Documentación Detallada
* [Detalle Completo del Proyecto 2 (Documentacion_Proyecto_Limpieza)](./Proyecto_02_Limpieza_Datos_BiciGo/Documentacion_Proyecto_Limpieza.docx)

---

## 3. Proyecto 3: Dashboard de Análisis Estratégico para la Expansión

### Título y Descripción
**Dashboard de Análisis Estratégico para la Expansión Nacional de BiciGo.**
Este proyecto convierte datos complejos en un panel de control visual y accionable, facilitando las decisiones de la gerencia sobre dónde concentrar el marketing y la expansión de operaciones.

### Problema y Objetivos
* **Problema de Negocio:** La gerencia carece de una herramienta visual consolidada para tomar decisiones basadas en datos sobre la expansión (dónde invertir) y la priorización de marketing.
* **Objetivos del Análisis:**
    1.  Visualizar rápidamente tendencias por región y temporada.
    2.  Crear un **Dashboard** accionable que comunique los hallazgos clave.

### Conjunto de Datos
* **Datos Utilizados:** Archivos consolidados de ventas, servicios y clientes (posterior a la limpieza).
* **Variables Clave:** `Región/Ciudad`, `Modelo más Arrendado`, `Frecuencia de Compra`.

### Metodología y Herramientas
* **Pasos Principales:** Análisis de Agregación, Visualización, Comunicación de Resultados.
* **Herramientas Usadas:** **Excel** (Tablas Dinámicas, Gráficos Dinámicos, Formato Condicional, Dashboard).
    * *Nota: La combinación de Tablas Dinámicas y Gráficos Dinámicos permite un reporte interactivo y eficiente.*

### Resultados y Conclusiones (Insights)
* **Hallazgo:** La Región Metropolitana concentra la mayor actividad (indicando potencial de expansión o saturación). Los clientes de servicios de mantención arriendan un 50% más.
* **Implicación de Negocio:** La expansión debe enfocarse primero en regiones de alta demanda comprobada. El programa de fidelización debe vincular el servicio de mantención con los beneficios de arriendo.

### Documentación Detallada
* [Detalle Completo del Proyecto 3 (Documentacion_Proyecto_Dashboard)](./Proyecto_03_Dashboard_Expansión/Documentacion_Proyecto_Dashboard.docx)



## 4. Proyecto 4: Análisis Inverso y Control de Gestión de Costos Logísticos

### Título y Descripción
** Análisis de Datos Inverso: Reconstrucción de Flujos y Control de Presupuesto Logístico.**
Este proyecto utiliza una metodología de ingeniería inversa para validar la integridad de reportes de gestión. A partir de un dashboard final de costos, se reconstruyó un conjunto de datos transaccionales "crudos" con el fin de simular procesos de limpieza y transformación, asegurando la trazabilidad absoluta entre el dato origen y los indicadores de cumplimiento presupuestario.

### Problema y Objetivos

* ** Problema de Negocio:** La falta de visibilidad sobre el origen de los datos en reportes consolidados puede ocultar ineficiencias o errores de cálculo en los promedios de gasto.

### Objetivos del Análisis:
Realizar un Análisis Inverso para generar un set de datos transaccionales coherente con los resultados finales de la Gerencia de Logística.

Monitorear el cumplimiento del Límite de Control Mensual (< $25M) mediante visualizaciones dinámicas.

### Conjunto de Datos

* ** Datos Utilizados:** Dataset transaccional reconstruido (simulado) con formatos de fecha mixtos y ruido digital para ejercicios de normalización.


* ** Variables Clave:** Mes-Año, Categoría de Gasto (Sueldos, Fletes, etc.), Monto (Miles de Pesos), Promedio Trimestral.

### Metodología y Herramientas

* ** Pasos Principales:** Ingeniería inversa de datos, Limpieza y Estandarización de registros, cálculo de promedios móviles y creación de Gráficos de Control de Procesos.


* ** Herramientas Usadas:** Excel (Fórmulas Lógicas, Validación de Datos, Gráficos de Líneas con Límites de Control y Formato Condicional).

### Resultados y Conclusiones (Insights)

* ** Hallazgo:** El costo total de la Gerencia para el año 2013 ascendió a $285.213 (miles de pesos), con un promedio mensual de $23.768. Se identificó que la categoría Sueldos domina el presupuesto con un 53% del gasto total.


* ** Implicación de Negocio:** El gasto se mantuvo bajo control durante el 90% del año, superando el límite de $25M únicamente en julio debido a peaks en infraestructura y fletes. Se recomienda mantener la vigilancia sobre los costos fijos de sueldos y la variabilidad trimestral en servicios de seguridad.


