# Spaceship Titanic - Kaggle Competition

## Descripción

Este proyecto fue desarrollado como parte de la competencia **Spaceship Titanic** en Kaggle. El objetivo de la competencia es predecir si los pasajeros fueron transportados a través de un viaje intergaláctico, utilizando un conjunto de datos que incluye características demográficas y de viaje de los pasajeros.

## Modelos Utilizados

Se implementaron y evaluaron seis modelos diferentes de machine learning para abordar este desafío:

1. **Regresión Logística Multinomial**: Modelo estadístico para predecir la probabilidad de que un pasajero pertenezca a una de las categorías de transporte.
2. **Análisis Discriminante Lineal (LDA)**: Método que busca encontrar una combinación lineal de características que separen mejor las clases de los pasajeros.
3. **Árbol de Decisión**: Modelo que utiliza una estructura de árbol para tomar decisiones basadas en las características de los pasajeros.
4. **Bagging**: Enfoque de ensemble que combina múltiples modelos de árboles de decisión para mejorar la estabilidad y precisión.
5. **Random Forest**: Extensión del bagging que utiliza un conjunto de árboles de decisión entrenados con subconjuntos aleatorios de los datos.
6. **Boosting con Gradient Boosting**: Método que combina múltiples modelos débiles para crear un modelo fuerte, ajustando iterativamente los errores de los modelos anteriores.

## Documentos incluídos
- [Reporte en formato ipynb](./Spaceship_Titanic.ipynb)
- [Reporte en formato html](./Spaceship_Titanic.html)

Nota: la base de datos de train y test puede encontrarse en Kaggle 
https://www.kaggle.com/competitions/spaceship-titanic
