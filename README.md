
## YELP & GOOGLE MAPS - REVIEWS AND RECOMMENDATIONS



![Logo](https://camo.githubusercontent.com/953e3aeda5322462b234c4dace6aa8796f4bc6e250efc943c4091b189a6b237e/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f612f61642f59656c705f4c6f676f2e7376672f3235363070782d59656c705f4c6f676f2e7376672e706e67)

![Logo](https://cdn.computerhoy.com/sites/navi.axelspringer.es/public/media/image/2023/02/google-maps-2961754.jpg?tf=1200x)


### Descripción del Proyecto
Este proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA) y un proceso de extracción, transformación y carga (ETL) en datos de reseñas de negocios de restaurantes y hoteles obtenidos de Yelp y Google Maps. Posteriormente, se implementará un pipeline en Google Cloud Platform (GCP) para procesar y almacenar los datos en un Data Warehouse en BigQuery. Finalmente, se desarrollará un dashboard interactivo utilizando Tableau para visualizar los insights obtenidos del análisis de datos y se implementará un sistema de recomendaciones basado en modelos de machine learning utilizando scikit-learn.

### Componentes del Proyecto
- Extracción de Datos: Se obtendrán datos de reseñas de negocios de restaurantes y hoteles de las APIs de Yelp y Google Maps utilizando bibliotecas como requests o bibliotecas específicas de Python para interactuar con estas APIs.

- Análisis Exploratorio de Datos (EDA): Se realizará un análisis exploratorio de los datos para entender su distribución, características principales y posibles patrones. Se utilizarán herramientas como Pandas, NumPy y visualizaciones gráficas con Matplotlib y Seaborn.

- Proceso de ETL: Se realizará la limpieza, transformación y preparación de los datos para su carga en BigQuery. Esto puede incluir la eliminación de valores nulos, la normalización de datos y la creación de nuevas características.

- Pipeline en Google Cloud Platform: Se creará un pipeline utilizando Apache Beam o Cloud Dataflow para procesar los datos de manera escalable y eficiente en GCP.

- Data Warehouse en BigQuery: Los datos procesados se cargarán en un almacén de datos en BigQuery para su posterior análisis y consulta.

- Desarrollo del Dashboard en Tableau: Se desarrollará un dashboard interactivo en Tableau para visualizar los resultados del análisis de datos. Esto incluirá gráficos, tablas y otros elementos visuales para presentar los insights obtenidos.

- Implementación de un Sistema de Recomendaciones: Se entrenará un modelo de machine learning utilizando scikit-learn para generar recomendaciones personalizadas basadas en las preferencias de los usuarios y las características de los negocios.

### Requisitos de Instalación
Para ejecutar el código de este proyecto, se requieren las siguientes dependencias:

Python 3.12
- Bibliotecas Python: pandas, numpy, matplotlib, seaborn, scikit-learn, requests
Tableau Desktop o Tableau Public

![Logo](https://miro.medium.com/v2/resize:fit:720/format:webp/0*suclCQicgkQsVRaf.png)


# Proyecto: Pipeline ETL con Apache Spark y Apache Airflow

Descripción
Este proyecto tiene como objetivo construir un pipeline ETL (Extract, Transform, Load) utilizando Apache Spark y Apache Airflow. El pipeline realizará la extracción de datos de archivos Parquet almacenados en HDFS, la transformación de estos datos utilizando Apache Spark y la carga de los datos transformados en una base de datos creada en Apache Spark.


![Logo](https://blog.allegro.tech/img/articles/2021-06-28-1-task-2-solutions-spark-or-beam/bigdata-projects-architecture.png)


## Requisitos Previos
- Docker instalado en el sistema local.
- Iniciar el contenedor Docker con el ambiente de Hadoop y Spark:

## Instalación y Configuración

Clonar el repositorio desde GitHub:

```bash
  git clone https://github.com/Bemontx/YELP-GOOGLE-MAPS---REVIEWS-AND-RECOMMENDATIONS
  cd YELP-GOOGLE-MAPS---REVIEWS-AND-RECOMMENDATIONS
```
    
## Ejecución
Iniciar Apache Spark:

```bash
  spark-shell
```
- Ejecutar los scripts de transformación de datos en Spark.

- Iniciar Apache Airflow:

```bash
  airflow scheduler
  airflow webserver
```
- Acceder al panel de Airflow en el navegador y activar el DAG para comenzar la ejecución del pipeline.
