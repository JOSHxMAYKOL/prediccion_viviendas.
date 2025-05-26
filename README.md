# Predicción de Precios de Viviendas con Redes Neuronales

## Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar modelos de Machine Learning para predecir precios de viviendas utilizando datos reales. Se implementa una regresión lineal simple y una red neuronal artificial, ambas usando Python y TensorFlow/Keras. Además, se visualizan los resultados y se aplican buenas prácticas de programación y control de versiones con GitHub.

## Metodología

1. **Análisis Teórico:**  
   Se investigaron los fundamentos de redes neuronales artificiales, regresión lineal y el uso de TensorFlow/Keras como herramienta para el desarrollo de modelos de aprendizaje automático. Se explicó la importancia del control de versiones con GitHub para la gestión eficiente del código.

2. **Preparación del Entorno:**  
   Se configuró un entorno de desarrollo con Python, instalando las librerías necesarias: TensorFlow, Keras, Matplotlib, NumPy, Pandas y Scikit-learn. Se inicializó un repositorio en GitHub para almacenar el proyecto.

3. **Implementación Práctica:**  
   - Se cargó el dataset California Housing disponible en Scikit-learn.  
   - Se aplicó regresión lineal simple para predecir el precio a partir de la variable promedio de habitaciones (`AveRooms`).  
   - Se construyó y entrenó una red neuronal con múltiples variables para mejorar la precisión de la predicción.  
   - Se graficaron los resultados para comparar valores reales y predicciones.  
   - Se utilizaron estructuras básicas de programación como listas y ciclos para calcular métricas de error.

## Resultados

- La regresión lineal simple permitió observar una relación lineal básica entre la cantidad promedio de habitaciones y el precio de la vivienda, aunque con limitaciones en precisión.  
- La red neuronal mostró mejor desempeño, ajustando mejor las predicciones a los valores reales gracias a la incorporación de múltiples variables y capas ocultas con activaciones no lineales.  
- Los gráficos generados muestran visualmente la aproximación de ambos modelos al conjunto de datos de prueba.  
- El error absoluto medio calculado con la red neuronal fue de aproximadamente *[indicar el valor que obtuviste]*, lo que indica un buen nivel de precisión para un modelo básico.

## Conclusiones Personales

- Las redes neuronales son herramientas potentes para capturar relaciones complejas entre variables que modelos lineales simples no pueden detectar.  
- TensorFlow/Keras facilita mucho la implementación y entrenamiento de modelos de Deep Learning con código claro y compacto.  
- El uso de control de versiones con GitHub es fundamental para mantener un historial organizado, colaborar y proteger el código.  
- Trabajar con datasets reales como el California Housing permite comprender mejor los retos y técnicas necesarias en proyectos de predicción.

---

## Cómo ejecutar el proyecto

1. Clonar este repositorio.  
2. Ejecutar el notebook `prediccion_viviendas.ipynb` en Google Colab o localmente.  
3. Revisar las celdas de código y gráficos para entender el flujo del proyecto.

---

## Autor

JOSH MAYKOL P. M.

---

