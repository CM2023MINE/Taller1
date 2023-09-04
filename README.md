# Análisis de Datos: Inversiones Inmobiliarias en Airbnb 📋

Este proyecto tiene como objetivo realizar un análisis de datos utilizando técnicas estadísticas y de visualización para ayudar a los inversionistas interesados en propiedades para alquiler a través de la plataforma Airbnb. A través del análisis de un conjunto de datos de propiedades listadas en Airbnb en una ciudad específica, buscamos identificar patrones, tendencias y oportunidades de inversión.

## Contenido del Repositorio 📖

Este repositorio contiene los siguientes elementos:

1. **Jupyter Notebooks**: Archivos Jupyter Notebook que contienen el código y el análisis de datos, archivo llamado **eda.ipynb**.

2. **Dataset**: El conjunto de datos utilizado para el análisis se obtuvo de [Boston](http://insideairbnb.com/boston/) y el archivo [Listings](http://data.insideairbnb.com/united-states/ma/boston/2023-06-21/data/listings.csv.gz).

3. **Informe Ejecutivo**: Un informe ejecutivo que resume las recomendaciones para los inversionistas.

## Actividades y Entregables 📝

### 1. Selección del Dataset de Trabajo

Seleccioné la ciudad [Boston](http://insideairbnb.com/boston/) y descargué el dataset de listings correspondiente desde [Listings](http://data.insideairbnb.com/united-states/ma/boston/2023-06-21/data/listings.csv.gz).

### 2. Entendimiento Inicial de Datos

- **Dimensiones del Dataset**: El dataset consta de **3973** filas y **75** columnas.
- **Tipos de Datos**: El dataset contiene atributos de diferentes tipos, como texto, números y fechas.
- **Atributos Importantes (Top 5)**:
    1. ```neighbourhood_cleansed```: es importante proporciona un contexto geográfico para los datos.
    2. ```number_of_reviews```: es relevante, ya que proporciona información sobre la popularidad, la calidad y la satisfacción de los huéspedes.
    3. ```has_availability```: es de gran importancia ya que proporciona información crítica sobre la disponibilidad de una propiedad.
    4. ```review_scores_value```: es indispensable el atributo ya que nos puede proporciona una evaluación específica de cómo los huéspedes perciben la relación calidad-precio de una propiedad o la vivienda.
    5. ```review_scores_rating```: esta variable nos proporciona una evaluación general de la calidad y la satisfacción de los huespedes en la propiedad o la vivienda.

### 3. Estrategia de Análisis 

Para abordar la necesidad del negocio de identificar las mejores opciones de inversión inmobiliaria, se utilizará la siguiente estrategia:

- **Análisis Descriptivo**: Se calcularán estadísticas descriptivas para comprender la distribución de los atributos clave, como percentiles, mediana, moda, desviación estandar.
- **Visualización de Datos**: Se utilizarán gráficos y visualizaciones para identificar patrones y tendencias, por ejemplo, histogramas, grafica de barras, diagrama de caja y bigotes.
- **Análisis Multivariado**: Se explorarán relaciones entre diferentes atributos para obtener insights más profundos, por ejemplo se realizo mapa de calor al momento de correlacionar variables o atributos del dataset, analisis de pareto.

### 4. Desarrollo de la Estrategia ✏️

Se implementará la estrategia de análisis, que incluirá procesamiento de datos, técnicas estadísticas y visualización de datos. Los resultados se documentarán en los Jupyter Notebooks.

### 5. Generación de Resultados

Se redactará un informe ejecutivo que recomendará a los inversionistas:

- Sectores de inversión recomendados.
- Tipos de propiedades recomendados.
- Rangos de precios sugeridos.
- Amenities u otros factores relevantes para la inversión.

## Requisitos de Ejecución ⚙️

Para ejecutar los Jupyter Notebooks y reproducir el análisis, sigue los pasos a continuación:

1. Abre los Jupyter Notebooks en orden **eda.ipynb**.

## Dataset 📚

El dataset utilizado para este análisis se encuentra en la carpeta **data** y está disponible en [Listings](http://data.insideairbnb.com/united-states/ma/boston/2023-06-21/data/listings.csv.gz).

## Referencias 🎯

 1. [data boston](http://insideairbnb.com/boston/).
 2. [seaborn](https://seaborn.pydata.org/).
 3. [pandas](https://pandas.pydata.org/).
 4. [matplotlib](https://matplotlib.org/).
 
## Autor 👤

**Carlos Montana**