# Imputación de datos de temperaturas faltantes mediante Predicción 

## Objetivo del Proyecto

En este proyecto, analizaremos un dataset de temperaturas correspondiente a cuatro ciudades de Argentina. Este conjunto de datos incluye registros temperatura mínima, máxima y promedio. Sin embargo, hemos encontrado que muchos de estos registros presentan datos faltantes.

El objetivo principal es desarrollar un modelo de machine learning o deep learning que, según la técnica que ofrezca mayor precisión, nos permita completar los datos ausentes de temperaturas.

Comenzaremos enfocándonos en la ciudad de Resistencia.

Se desarrolla y evalúa cinco modelos de aprendizaje supervisados para predecir temperaturas en función de los datos disponibles:

1. Utilizaremos los datos de **TAVG** , **TMAX** y **LLOVIO** para predecir **TMIN**.
2. Utilizaremos los datos de **TAVG** , **TMIN** y **LLOVIO** para predecir **TMAX**.
3. Utilizaremos los datos de **TMAX** , **TMIN** y **LLOVIO** para predecir **TAVG**.
4. Utilizaremos los datos de **TAVG**  , **LLOVIO** para predecir **TMIN** y **TMAX**
5. Utilizaremos los datos de **TMIN**  , **LLOVIO** para predecir **TAVG** y **TMAX**
6. Utilizaremos los datos de **TMAX**  , **LLOVIO** para predecir **TMIN** y **TMAX**