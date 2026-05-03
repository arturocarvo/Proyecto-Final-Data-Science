# Proyecto-Final-Data-Science
Este proyecto aplica técnicas de Ciencia de Datos sobre un dataset real de logística (Tienda Nube) con envíos de moto en CABA.

Parte 1: NLP (Preprocesamiento de Texto)
Se trabajó sobre la columna "Notas del comprador" para normalizar instrucciones de entrega.

Tarea 1: Tokenización. Separación de oraciones en palabras individuales.

Tarea 2: Eliminación de Stopwords. Filtrado de conectores y palabras sin peso semántico en español.

Herramientas: NLTK y expresiones regulares.

Parte 2: Deep Learning (Modelo Base)
Construcción de una Red Neuronal Sencilla para clasificación binaria.

Objetivo: Predecir la categoría de ticket (Alto/Bajo valor).

Variables: Subtotal de productos y día de la semana.

Arquitectura: Una capa densa con función de activación Sigmoid.

Parte 3: Profundización (TP Final)
Se optimizó el modelo inicial transformándolo en una Red Neuronal Profunda.

Mejoras:

Adición de 3 capas ocultas (32, 16 y 8 neuronas).

Implementación de Dropout (0.2) para evitar el sobreajuste.

Uso del optimizador Adam y aumento a 30 épocas.

Resultado: Precisión final del 98.48% en la clasificación de pedidos.

Tecnologías utilizadas
Python (Google Colab)

Pandas (Gestión de datos)

NLTK (Procesamiento de Lenguaje Natural)

TensorFlow / Keras (Redes Neuronales)
