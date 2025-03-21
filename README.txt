# Análisis de Calidad del Vino - Proyecto de Machine Learning

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar y predecir la calidad del vino tinto utilizando un conjunto de datos público. El análisis incluye la exploración de datos, preprocesamiento, balanceo de clases, selección de características y la aplicación de varios modelos de machine learning para evaluar su desempeño.

El dataset utilizado proviene del artículo científico:
> P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.  
> Modeling wine preferences by data mining from physicochemical properties.  
> In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.

El dataset está disponible en formato CSV (`winequality-red.csv`) y contiene características fisicoquímicas del vino tinto, junto con una variable objetivo (`quality`) que representa la calidad del vino en una escala de 0 a 10.

## Archivos en la Carpeta

1. **Notebook Principal (`nombre_actual_del_notebook.ipynb`)**  
    Este notebook contiene el análisis principal del dataset de calidad del vino. Incluye:
    - Exploración de datos y visualización.
    - Preprocesamiento de datos, incluyendo normalización y balanceo de clases con SMOTE.
    - Aplicación de varios modelos de machine learning:
      - K-Nearest Neighbors (KNN)
      - Logistic Regression
      - Decision Tree