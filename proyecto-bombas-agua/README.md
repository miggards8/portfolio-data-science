# Predicción del Estado de Bombas de Agua (Competición "Pump it Up")

Proyecto de Data Science desarrollado en el contexto de la competición *Pump it Up: Data Mining the Water Table*, organizada por DrivenData. El objetivo es predecir el estado operativo de bombas de agua en Tanzania a partir de datos geográficos, técnicos y administrativos.


## 📁 Datos

Los datos provienen de la competición oficial y están disponibles públicamente. Se incluyen en la carpeta `datos/`.

## 🛠 Herramientas y técnicas utilizadas

- Python (pandas, scikit-learn, XGBoost)
- Ingeniería de variables y codificación categórica
- Selección de variables por importancia
- Validación cruzada
- MLflow para seguimiento de experimentos y selección del mejor modelo.

## 🎯 Objetivo

Clasificar las bombas en:
- Funcionales
- Funcionales con necesidad de reparación
- No funcionales

## 📊 Resultados

- Accuracy pública: 0.8160
- Modelo final: XGBoost con selección de las 200 variables más importantes
