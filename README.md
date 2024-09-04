# LSTM Sales Prediction Model

Este proyecto utiliza una red neuronal recurrente (LSTM) para predecir las ventas futuras en función de una serie temporal de datos de ventas. 

## Descripción del Proyecto

El objetivo del proyecto es modelar y predecir las ventas del día siguiente usando una combinación de datos numéricos y categóricos. Se utilizan modelos de redes neuronales LSTM, optimizados mediante una búsqueda de hiperparámetros con `Keras Tuner`, para mejorar el rendimiento de las predicciones.

### Componentes Clave del Proyecto

1. **Exploración de Datos (EDA)**: Incluye un análisis detallado de las características de las ventas y la distribución de las mismas a lo largo del tiempo.
2. **Modelos de Árbol de Decisión y Ensamble**: Se probaron diferentes modelos de machine learning, incluidos árboles de decisión y modelos en ensamble como `RandomForest`, para obtener una primera línea base de rendimiento.
3. **Modelado con LSTM**: La red neuronal LSTM fue utilizada para capturar las secuencias de ventas y predecir las futuras ventas.
4. **Optimización de Hiperparámetros**: Utilizamos `Keras Tuner` para ajustar los hiperparámetros clave del modelo LSTM y maximizar su rendimiento.
5. **Predicción a Futuro**: El modelo predice las ventas para los próximos 30 días basándose en los datos históricos.

## Estructura del Proyecto

- **Exploración de Datos**: Análisis de tendencias, estacionalidad y patrones de ventas.
- **Preprocesamiento de Datos**: Transformación de las características categóricas a formato numérico y escalado de los datos.
- **Modelado LSTM**: Construcción y entrenamiento de modelos con capas LSTM para capturar la secuencia temporal de los datos.
- **Optimización de Modelos**: Uso de Keras Tuner para ajustar parámetros como el tamaño de las capas LSTM y la tasa de aprendizaje.
- **Evaluación**: Cálculo del RMSE y gráfico comparativo de las predicciones vs los valores reales, incluyendo un área sombreada de error.

## Requisitos

- Python 3.x
- TensorFlow
- Keras Tuner
- Matplotlib
- scikit-learn
- pandas
- numpy
