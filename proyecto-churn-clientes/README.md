# Modelo Predictivo de Fuga de Clientes

Este proyecto aplica técnicas de Machine Learning para predecir la probabilidad de que un cliente abandone una empresa de telecomunicaciones (churn). Está dividido en tres etapas: preprocesamiento, modelado y predicción final.

## 📁 Estructura del proyecto

- `1_preprocesado.ipynb`: Limpieza de datos, imputación, codificación de variables y análisis exploratorio.
- `2_modelado.ipynb`: Entrenamiento de varios modelos, validación cruzada, selección del mejor modelo.
- `3_prediccion.ipynb`: Aplicación del modelo final sobre nuevos datos y análisis de resultados.

## 📁 Datos

Los datos se encuentran en `datos` separados en clientes de Diciembre y de Enero y están incluidos en este repositorio. Son datos públicos de simulación de clientes de telecomunicaciones.

## 🛠 Herramientas utilizadas

- Python, pandas, scikit-learn
- Visualización: seaborn, matplotlib
- Guardado de modelos: joblib

## 📊 Resultados destacados

- Identificación temprana de clientes con alto riesgo de fuga.
- Comparación entre distintos clasificadores.
- Visualización de variables más influyentes en la predicción.
