# Predicción de Precios de Viviendas con Redes Neuronales

## Objetivo

Investigar los fundamentos de redes neuronales y regresión lineal, y aplicar estos conocimientos para construir, entrenar y evaluar modelos que predigan precios de viviendas utilizando Python y TensorFlow/Keras. Además, integrar visualización de datos y control de versiones con GitHub.

---

## Preguntas Teóricas

### ¿Qué es una red neuronal artificial?

Una red neuronal artificial es un modelo computacional inspirado en las neuronas del cerebro humano, compuesto por capas de nodos (neuronas) interconectados que procesan información para aprender patrones complejos y resolver problemas de clasificación o regresión.

### ¿Qué es una regresión lineal y cómo se aplica en Machine Learning?

La regresión lineal es un método estadístico que modela la relación entre una variable dependiente y una o más variables independientes mediante una función lineal. En Machine Learning, se usa para predecir valores continuos ajustando una línea que minimice el error entre las predicciones y los datos reales.

### ¿Para qué sirve TensorFlow/Keras en el desarrollo de modelos de Machine Learning?

TensorFlow es una biblioteca de código abierto para computación numérica y aprendizaje automático que facilita la creación y entrenamiento de modelos complejos, incluyendo redes neuronales. Keras es una API de alto nivel que simplifica la construcción de modelos sobre TensorFlow con una sintaxis intuitiva y rápida.

### ¿Por qué es importante el control de versiones con GitHub?

GitHub permite gestionar y mantener un historial ordenado de los cambios realizados en el código fuente, facilitando la colaboración, recuperación de versiones previas, y asegurando un desarrollo organizado y seguro.

---

## Metodología

1. **Preparación del entorno:**  
   - Instalación de Python y librerías: TensorFlow, Keras, Matplotlib, NumPy, Pandas, Scikit-learn.  
   - Creación e inicialización del repositorio en GitHub con archivo README.md.

2. **Carga y análisis del dataset:**  
   - Se utilizó el dataset California Housing de Scikit-learn con características relevantes de viviendas y precios.

3. **Implementación de modelos:**  
   - **Regresión lineal simple:** predicción basada en una sola variable (`AveRooms`).  
   - **Red neuronal:** modelo secuencial con varias capas y activaciones ReLU, entrenado con múltiples variables para mejorar la predicción.

4. **Visualización de resultados:**  
   - Gráficos de dispersión para comparar predicciones vs valores reales.  
   - Cálculo y presentación del error absoluto medio.

5. **Control de versiones:**  
   - Subida y actualización del código y documentación en GitHub para mantener un registro de avances y facilitar la entrega.

---

## Resultados

- La regresión lineal simple mostró una relación básica entre el promedio de habitaciones y el precio de vivienda, con limitaciones en precisión.  
- La red neuronal logró una mejor aproximación a los valores reales al considerar múltiples características y capas ocultas.  
- El error absoluto medio del modelo de red neuronal fue de aproximadamente **[colocar valor obtenido al ejecutar]**.  
- Los gráficos reflejaron visualmente la mejora en la predicción con el uso de redes neuronales.

---

## Conclusiones Personales

- La regresión lineal es útil para entender relaciones simples, pero tiene limitaciones cuando los datos presentan relaciones complejas.  
- Las redes neuronales permiten capturar patrones no lineales y múltiples variables para mejorar la predicción.  
- TensorFlow/Keras es una herramienta potente y accesible para implementar modelos de Deep Learning.  
- El uso de GitHub es fundamental para mantener la integridad del proyecto y colaborar eficazmente.  
- Trabajar en Google Colab facilita la experimentación con recursos en la nube sin complicaciones de instalación local.

---

## ¿Cómo ejecutar el proyecto?

1. Clonar el repositorio con:  
   ```bash
   git clone <URL_del_repositorio>

## Autor

JOSH MAYKOL P. M.

---

