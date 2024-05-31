# Link de Sustentación:
[Ver Sustentación del Proyecto 3](https://www.youtube.com/watch?v=HOxdG6BZRss)

### Info de la Materia: Topicos Especiales en Telematica-st0263

### Estudiantes:
- Miguel Angel Martinez Florez, mamartinef@eafit.edu.co

### Profesor:  Edwin Nelson Montoya Munera, emontoya@eafit.edu.co  

# Proyecto 3: Spark con Notebooks y PySpark.

##  Objetivo
El objetivo principal de este proyecto es analizar datos sobre casos de COVID-19 en Colombia con el fin de obtener información valiosa para la gestión de la pandemia. El análisis se realizará utilizando las herramientas de Big Data Spark y SparkSQL, y se enfocará en responder preguntas de negocio relevantes relacionadas con la distribución geográfica y temporal de los casos, la distribución por edades y otras variables de interés.

## Descripción de la Actividad
La actividad se desarrolla en las siguientes etapas:

1) Obtención y preparación de datos:

- Descargar el dataset de casos de COVID-19 desde la fuente oficial ([se quitó una URL no válida]).
- Almacenar el dataset en un bucket de AWS S3 y en Google Drive.
- Cargar el dataset en un DataFrame de Spark.
- Realizar un análisis exploratorio de los datos para comprender su estructura, tipos de datos y valores.
- Limpiar y preprocesar los datos si es necesario.

2) Análisis de datos con Spark DataFrames:

- Utilizar Spark DataFrames para realizar las siguientes tareas:
- Identificar los 10 departamentos con más casos de COVID-19.
- Identificar las 10 ciudades con más casos de COVID-19.
- Identificar los 10 días con más casos de COVID-19.
- Analizar la distribución de casos por edades.
- Formular y responder una pregunta adicional sobre los datos (por ejemplo, ciudad con mayor promedio de casos diarios).
- Aplicar técnicas de análisis de datos como filtrado, agrupación, agregación y ordenamiento.
- Visualizar los resultados del análisis utilizando gráficos y tablas.

3) Análisis de datos con SparkSQL:

- Repetir las mismas tareas que en Spark DataFrames utilizando consultas SQL.
- Aprovechar las capacidades de SQL para realizar análisis más complejos y eficientes.
- Integrar consultas SQL con código Scala para mayor flexibilidad.

4) Almacenamiento de resultados:
- Guardar los resultados del análisis en el bucket público de S3 y Google Drive.
- Exportar los resultados a formatos de archivo como CSV o JSON para su posterior uso.
- Documentar el proceso de análisis y los resultados obtenidos.

5. Presentación del proyecto:

- Elaborar un notebook .ipynb que contenga el código fuente del análisis y las visualizaciones.
- Grabar un video de sustentación del proyecto (máximo 10 minutos) que explique el análisis realizado y los resultados obtenidos.
- Enviar al profesor por correo electrónico:
- El notebook .ipynb con el análisis.
- La URL del S3 con los datos de entrada y salida.
- La URL del video de la sustentación del proyecto.

## Arquitectura del Reto
La arquitectura del reto se basa en las siguientes tecnologías:

- Spark: Un marco de computación en paralelo distribuido para el procesamiento de grandes conjuntos de datos.
- Spark DataFrames: Una API de alto nivel para trabajar con datos estructurados en Spark.
- SparkSQL: Un lenguaje de consulta SQL para interactuar con datos en Spark.
- AWS S3: Un servicio de almacenamiento de objetos en la nube para almacenar los datos y los resultados del análisis.
- Google Drive: Un servicio de almacenamiento en la nube para almacenar los datos y los resultados del análisis.
- JupyterHub: Un entorno de desarrollo web para ejecutar notebooks y código Python.
- Google Colab: Un entorno de ejecución en la nube para ejecutar notebooks y código Python.
