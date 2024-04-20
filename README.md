# Proyecto Mineria de Datos

El notebook abarca desde la limpieza y preprocesamiento de datos hasta el modelado y evaluación de diferentes técnicas de análisis de datos, incluyendo regresión, series temporales y clustering.

Breve explicación:

Lectura y Preprocesamiento de Datos: Se lee el archivo "FEV_data.csv", se realiza una exploración inicial de los datos, se transforman las variables categóricas en tipo 'category' y se elimina una columna que no aporta información. Luego se realiza un análisis de las relaciones entre las variables predictoras y la variable objetivo "Fev".

Modelado de Regresión: Se ajusta un modelo de regresión lineal utilizando las variables predictoras seleccionadas y se evalúa su desempeño, interpretando los coeficientes estimados.

Validación Cruzada y Evaluación de Modelo: Se aplica validación cruzada repetida al modelo de regresión para evaluar su capacidad de generalización.

Análisis de Serie Temporal: Se trabaja con un conjunto de datos de series temporales, se realiza una transformación Box-Cox para estabilizar la varianza, se ajustan modelos de suavizado y ARIMA, y se evalúan en términos de adecuación residual.

Análisis de Clustering: Se exploran métodos de clustering jerárquico y K-means para segmentar clientes en grupos similares. Se selecciona el número óptimo de clusters y se ajusta un modelo K-means. Luego se interpreta el biplot generado por PCA para visualizar los grupos en un espacio bidimensional.
