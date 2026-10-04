# Objetivo

Aplicar conocimientos de versionado, organización y análisis exploratorio de datos con pandas sobre un dataset real de operaciones portuarias.

## Introducción y Contexto del problema

### Sprint 1

El Puerto Fluvial de Rosario es uno de los complejos portuarios más importantes de América del Sur, siendo el principal punto de exportación de granos y derivados de la Argentina. Diariamente ingresan y egresan decenas de buques de distintas banderas con cargas de diverso tipo.

El sistema de registro de movimientos portuarios fue migrado recientemente desde un sistema heredado de los años '90. Ese sistema acumuló durante décadas inconsistencias de formato en fechas, matrículas de buques y valores numéricos fuera de rango, generando registros que no pueden incorporarse directamente al nuevo sistema.

Nuestro equipo fue contratado para analizar y depurar los datos del sistema antiguo.

Descargar el dataset [port_movements](https://raw.githubusercontent.com/HAD141/datasets/refs/heads/main/TrabajosPracticos/port_log/port_movements.csv)

`https://raw.githubusercontent.com/HAD141/datasets/refs/heads/main/TrabajosPracticos/port_log/port_movements.csv`

---

### Sprint 2 (sprint actual)

**Objetivo:** aplicar conocimientos de tratamiento de imágenes y programación
limpia sobre el contexto del sistema portuario.

Los radares ubicados en los accesos a los muelles capturan evidencia
fotográfica de las infracciones de velocidad. Las cámaras toman fotografías de
la zona de proa donde está pintada la matrícula del buque. A veces el sistema
recorta la zona de matrícula (`plates`) y otras entrega la imagen completa
(`completes`).

No todas las infracciones tienen imagen asociada, no todas las imágenes
corresponden a una infracción real (falsos positivos del radar) y puede haber
errores de detección óptica (imágenes borrosas, nocturnas o lejanas).

El objetivo es responder: **¿qué infracciones tienen evidencia visual válida?**

Se utilizan el dataset procesado en el Sprint 1 y el
[dataset de imágenes](https://github.com/HAD141/datasets/raw/refs/heads/main/TrabajosPracticos/port_log/port_log_images.zip).
