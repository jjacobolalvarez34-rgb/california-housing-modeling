# California-House-Modeling

Proyecto académico de machine learning desarrollado durante el curso de Modelación y Simulación I como parte del programa de Matemáticas.

El objetivo de este proyecto fue analizar un conjunto de datos de viviendas en California y construir modelos predictivos capaces de estimar el precio de las propiedades a partir de características físicas, geográficas y socioeconómicas.

---

## Objetivos

* Realizar Análisis Exploratorio de Datos (EDA).
* Identificar variables relevantes para la predicción de precios.
* Aplicar técnicas de limpieza y preprocesamiento de datos.
* Construir y comparar diferentes modelos predictivos.
* Evaluar el desempeño de los modelos mediante métricas de regresión.
* Analizar comportamientos de subajuste (underfitting) y sobreajuste (overfitting).

---

## Metodología

### Análisis Exploratorio de Datos (EDA)

* Estadística descriptiva.
* Detección de valores atípicos (outliers).
* Análisis de correlaciones.
* Visualización de datos.
* Análisis geográfico utilizando variables de latitud y longitud.

### Preprocesamiento de Datos

* Imputación de valores faltantes.
* One-Hot Encoding.
* Escalamiento de variables.
* Selección de características.

### Modelos Predictivos

* Regresión Lineal.
* Regresión Ridge.
* Regresión Lasso.
* Regresión Polinómica.
* Random Forest Regressor.
* Redes Neuronales (MLP).

### Optimización de Modelos

* Ajuste de hiperparámetros.
* Comparación de modelos.
* Evaluación de desempeño.

---

## Métricas de Evaluación

Los modelos fueron evaluados utilizando:

* R² Score (Coeficiente de Determinación).
* RMSE (Root Mean Squared Error).
* MAE (Mean Absolute Error).

---

## Tecnologías Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* TensorFlow / Keras (cuando aplica)

---

## Resultados

### Análisis de Correlación

![Correlation Matrix](images/correlation_matrix.png)

La matriz de correlación permitió identificar relaciones entre las variables numéricas y su influencia sobre el precio de las viviendas.

### Distribución de la Variable Objetivo

![Target Distribution](images/target_distribution.png)

Se analizó la distribución de la variable objetivo para comprender su comportamiento e identificar posibles asimetrías que afectaran el desempeño de los modelos.

### Comparación de Modelos

![Model Comparison](images/model_comparison.png)

Se compararon múltiples modelos de regresión utilizando métricas como R², MSE y MAE. El modelo Random Forest obtuvo el mejor desempeño predictivo entre las alternativas evaluadas.

### Valores Reales vs Predichos

![Actual vs Predicted](images/actual_vs_predicted.png)

Esta visualización compara los valores reales de las viviendas con las predicciones generadas por el modelo Random Forest optimizado.

### Importancia de Variables

![Feature Importance](images/feature_importance.png)

El análisis de importancia de variables permitió identificar las características con mayor influencia en la estimación del precio de las viviendas.

### Análisis Geográfico

![California Housing Map](images/california_housing_map.png)

La distribución geográfica de las observaciones fue explorada mediante las variables de latitud y longitud para identificar patrones espaciales asociados a los precios de las viviendas.

---

## Estructura del Repositorio

```text
california-housing-modeling
│
├── README.md
├── README_ES.md
├── California_House_Prices_Prediction.ipynb
├── california_house_prices_prediction.py
│
├── data/
│
├── images/
│   ├── correlation_matrix.png
│   ├── target_distribution.png
│   ├── actual_vs_predicted.png
│   ├── model_comparison.png
│   ├── feature_importance.png
│   └── california_housing_map.png
```

---

## Autor

Jacobo Lopez

Estudiante de Matemáticas

Fundación Universitaria Konrad Lorenz

Colombia
