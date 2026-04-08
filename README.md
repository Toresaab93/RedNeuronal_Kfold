# Predicción de Abandono de Clientes (Churn) con Deep Learning y ML

Este repositorio contiene un análisis completo de clasificación para predecir la fuga de clientes. 
## Proceso
* **Optimización Automática:** Uso de `GridSearchCV` para encontrar la mejor arquitectura (Batch size, Epochs, Optimizers).
* **Validación Robusta:** Implementación de `K-Fold Cross Validation` (cv=10) para garantizar que la precisión sea real y no aleatoria.
* **Deep Learning:** Red Neuronal construida con Keras/TensorFlow y SciKeras.
* **Comparativa:** Análisis de rendimiento frente a modelos como KNN y Naive Bayes.

## 📈 Resultados Finales
* **Mejor Modelo:** ANN (Adam Optimizer, 500 Epochs).
* **Precisión (Accuracy) Media:** 84.86%
* **Frameworks:** TensorFlow, Keras, Scikit-Learn, SciKeras, Pandas.

## 🛠️ Cómo ejecutar
1. Clonar el repo.
2. Abrir el archivo `.ipynb` en VS Code o Jupyter.
3. El entorno requiere las librerías listadas en `requirements.txt`.
