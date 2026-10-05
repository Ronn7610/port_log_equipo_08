# CHANGELOG

# Sprint 2

## [Ejercicio 03]

- Creación de la función `aplicar_transformacion` para el preprocesamiento.
- Conversión a escala de grises en `03_01_gray`.
- Ecualización de histograma en `03_02_equalized`.
- Suavizado gaussiano en `03_03_blur`.
- Detección de bordes con Canny en `03_04_canny` (umbrales 250 y 400).
- Se ignoran en git las imágenes procesadas por ser regenerables.

## [Ejercicio 02]

- Listado de las imágenes disponibles con su tamaño en KB.
- Separación de las imágenes en los grupos `plates` y `completes`.
- Creación de `group_images` y guardado en `port_log/data/interim/group_images.json`.
- Cálculo de la resolución, el área y el tamaño promedio de cada grupo.
- Creación de la función `mostrar_muestra`.

## [Ejercicio 01]

- Clonación del repositorio del Sprint 1 y creación de la rama `Sprint_2`.
- Descarga y descompresión del dataset de imágenes en `port_log/data/raw/imgs`.
- Verificación de los archivos del Sprint 1 y conteo de sus registros.
- Actualización del `README.md` con el contexto del Sprint 2.

# Sprint 1

## [Ejercicio 07]

- Análisis a modo de conclusión sobre el trabajo realizado, la calidad de los datos y los patrones de infracción.
- Propuesta de un schema y validaciones para mejorar la captura de datos.
- Creación del archivo `port_log/reports/conclusion.md`.

## [Ejercicio 06]

- Cálculo del porcentaje de infracciones con fecha inválida.
- Cálculo del porcentaje de infracciones con hora inválida.
- Identificación del tipo de carga más frecuente.
- Identificación del origen más frecuente de los buques infractores.
- Cálculo de la duración promedio de estadía en muelle.

## [Ejercicio 05]

- Creación de gráficos para el análisis de las infracciones.
- Gráfico del top 10 de matrículas más reincidentes.
- Gráfico de infracciones por turno.
- Gráfico de infracciones por mes.
- Histograma y curva KDE del exceso de velocidad real.
- Gráfico del exceso de velocidad promedio por muelle.
- Gráfico de fechas válidas e inválidas.
- Exportación de los gráficos en formato JPG.

## [Ejercicio 04]

- Creación de la clase `PortAnalyzer`.
- Implementación de métodos para analizar infracciones por matrícula, turno, exceso de velocidad, muelle y tipo de carga.
- Creación del objeto `PortAnalyzer` e invocación de sus métodos.

## [Ejercicio 03]

- Normalización de fechas y horas (y transformación a datetime).
- Cálculo de la duración horas entre ingreso y egreso.
- Normalización de matrículas y muelles.
- Eliminación de registros con nulos en columnas críticas.
- Detección y eliminación de outliers mediante IQR.
- Cálculo del exceso de velocidad real y con tolerancia (5%).
- Eliminación de registros sin infracción.
- Guardado del dataset limpio y del resumen estadístico.

## [Ejercicio 02]
- Descarga y almacenamiento del dataset en `data/raw/port_movements.csv`.
- Análisis de los tipos de datos.
- Identificación de columnas que requieren conversión.
- Análisis de valores nulos y completitud del dataset.

## [Ejercicio 01]

- Inicialización y configuración del repositorio.
- Creación de la rama Sprint_1.
- Configuración del repositorio remoto.
- Creación de la estructura de directorios del proyecto.
- Creación del README.md y del CHANGELOG.md
