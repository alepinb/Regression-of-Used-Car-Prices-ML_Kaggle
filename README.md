# Regression of Used Car Prices - ML Kaggle

Este proyecto tiene como objetivo predecir el **precio de autos usados** utilizando varios atributos del vehículo. Utilizamos técnicas de **Machine Learning** y **análisis de datos** para crear un modelo que realice predicciones precisas basadas en la información disponible en el dataset.

## Estructura del Proyecto

```
proyecto_regresion/
├── data/
│   └── # Contiene los datos utilizados para el análisis y entrenamiento del modelo
├── analisis_de_datos.ipynb
├── entrenamiento_del_modelo.ipynb
├── submission.csv
└── submission_b.csv
```

* `data/`: Contiene los datos utilizados para el análisis y entrenamiento del modelo.
* `analisis_de_datos.ipynb`: Notebook donde se realiza el análisis exploratorio de los datos (EDA).
* `entrenamiento_del_modelo.ipynb`: Notebook con el entrenamiento del modelo de regresión.
* `submission.csv`: Archivo de predicciones generadas para el conjunto de prueba.
* `submission_b.csv`: Alternativa de predicciones con otro enfoque.

## Descripción de los Datos

El dataset contiene los siguientes atributos principales:

* **Power_HP**: Potencia del motor en caballos de fuerza.
* **Cylinders**: Número de cilindros del motor.
* **Engine_Size**: Tamaño del motor en litros.
* **Fuel_Type**: Tipo de combustible utilizado.
* Entre otros atributos importantes relacionados con las características del vehículo.

## Metodología

1. **Análisis Exploratorio de Datos (EDA)**: En `analisis_de_datos.ipynb` se realiza un análisis exploratorio, identificando las relaciones entre los atributos y el precio del auto.

2. **Entrenamiento del Modelo**: En `entrenamiento_del_modelo.ipynb` se desarrollaron varios modelos de **regresión**, incluyendo:
   * **Regresión Lineal**
   * **Random Forest**
   * **XGBoost**

   Se realizaron pruebas con validación cruzada y ajuste de hiperparámetros para seleccionar el mejor modelo.

3. **Predicciones**: El archivo `submission.csv` contiene las predicciones finales generadas por el mejor modelo seleccionado.

## Resultados

El mejor modelo alcanzó una precisión adecuada en la predicción del precio de autos usados, proporcionando información valiosa para la toma de decisiones en el mercado de vehículos.

## Requisitos

Para ejecutar el proyecto, asegúrate de tener instaladas las siguientes dependencias:

* `scikit-learn`
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `xgboost`

Puedes instalarlas usando:

```bash
pip install -r requirements.txt
```

### Autores

Alejandra Piñango - Desarrollador Principal - (https://github.com/alepinb)
