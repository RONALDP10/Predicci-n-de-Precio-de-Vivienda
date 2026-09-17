# Predicción de precios de viviendas

## Descripción del proyecto

Este proyecto de ciencia de datos tiene como objetivo analizar las características de diferentes viviendas y desarrollar modelos predictivos para estimar sus precios de venta.

Se utiliza una base de datos obtenida de Kaggle, aplicando técnicas de análisis exploratorio, limpieza de datos, ingeniería de variables y modelado predictivo.

## Objetivos

* Analizar la distribución de los precios de las viviendas.
* Identificar características relacionadas con el precio de venta.
* Preparar y transformar los datos para su modelado.
* Desarrollar y evaluar modelos de regresión.
* Identificar oportunidades de mejora para futuras versiones.

## Herramientas y tecnologías

* Python 

## Fuente de datos

Dataset: House Price Prediction (https://www.kaggle.com/datasets/debayank2024/house-price-prediction/data)

Los datos contienen características de las viviendas, como superficie, número de habitaciones, baños, ubicación, condición y año de construcción.

## Metodología

1. Exploración y comprensión de los datos.
2. Limpieza y tratamiento de valores inconsistentes.
3. Análisis exploratorio de datos (EDA).
4. Ingeniería y selección de variables.
5. Modelado.
6. Evaluación y comparación de resultados.

## Modelos y evaluación

Se desarrollaron dos modelos de regresión para estimar el precio de las viviendas. Los modelos desarrollados son Linear Regression y Randon Forest

Las métricas de evaluación consideradas incluyen:

* MAE: error absoluto medio.
* RMSE: raíz del error cuadrático medio.
* R²: proporción de variabilidad explicada por el modelo.

## Principales hallazgos

* Los modelos presentaron resultados similares en las métricas de evaluación aplicadas, siendo el modelo de Regresión lineal el que mejor desempeño global presenta.
* Se encontraron precios de valor 0 o de valor extremadamente excesivo, que considerando aspectos como cantidad de registros e inconsistencia se optó por eliminarlos.
* El error presentado en ambos modelos es considerable considerando la media de $460000 del precio de las viviendas. Se entiende que esto puede estar influenciado por la base de datos en sí, como por la falta de algunos otros factores que un tasador consideraría importante, la falta de datos en categorias de variables predictoras importantes, o la notable presencia de valores atípicos.


