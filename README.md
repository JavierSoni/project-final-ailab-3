# Clasificación de Células Sanguíneas

## 🎯 Objetivo
Clasificar la calidad de un vino.

## 🧬 Dataset
- **Etiquetas**: Archivo `winequality.csv` que contiene los nombres de archivo y sus respectivas clases.

## 🧠 Arquitectura del Modelo
 es un modelo de ExtraTreesRegressor

## 🧪 Métricas de Evaluación
- MAE
- MSE

## 📈 Resultados
- MAE en conjunto de validación: 41%
- MAE en conjunto de validación: 33%

## 📂 Estructura del Proyecto
- `notebooks/`: Contiene los notebooks para preprocesamiento, entrenamiento y evaluación.
- `data/`: Contiene las imágenes y el archivo de etiquetas.
- `artifacts/`: Almacena el modelo entrenado.
- `mlruns/`: Directorio generado por MLflow para el seguimiento de experimentos.

## 🛠️ Requisitos
Ver `requirements.txt` para las dependencias necesarias.
