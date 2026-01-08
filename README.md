# 📊 Análisis Exploratorio de Opciones Financieras

## 📌 Descripción
Proyecto de análisis exploratorio de datos (EDA) sobre un dataset de opciones financieras.
El objetivo es entender el comportamiento del mercado desde una perspectiva **comercial** y **financiera**, analizando volumen, precios, vencimientos, volatilidad y probabilidad de ejercicio.

Dataset obtenido desde HuggingFace.

## 🧠 Preguntas que se analizaron
- ¿Qué subyacentes concentran mayor volumen operado?
- ¿Cómo evoluciona el volumen a lo largo del tiempo?
- ¿Aumenta la actividad cerca del vencimiento?
- ¿Cuál es la relación entre precio, riesgo y probabilidad de ejercicio?
- ¿Cómo influye el moneyness (OTM%) en el precio y la probabilidad de éxito?

## 🛠️ Herramientas utilizadas
- Python
- pandas
- numpy
- matplotlib
- plotly

## 📈 Dashboard (Power BI)

### Páginas
-Información General del dataset
-Actividad y Vencimiento de los contratos (análisis comercial)
-Riesgo y Valoración (análisis financiero)


## 📊 Principales hallazgos
- El volumen tiende a incrementarse cerca del vencimiento.
- Las opciones ATM presentan mayor probabilidad de ejercicio.
- Las opciones OTM son más baratas pero significativamente más riesgosas.
- El mercado combina estrategias especulativas y de cobertura.

## 📎 Dataset
Fuente: https://huggingface.co/datasets/gauss314/opciones
