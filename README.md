# Vicomtech_workshop
Presentation of Vicomtech @ 42Urduliz, 26/10/2023

La workshop se realizó en [Google Colab](https://colab.google/notebooks/).

Tras una presentación para explicar las características de deep learning y machine learning, así como sus diferencias, pasamos a una prueba práctica.
Empezando por [AI_HEART_DISEASE](files/AI_HEART_DISEASE.ipynb), se nos facilita un [archivo csv](files/archive.zip) (subido comprimido) con información sin procesar. Nuestro objetivo es cargarlo en Python, hacerlo más legible para una IA (ej: pasar de "sexo: M/F" a dos variables "Sexo_M: 0/1, Sexo_F: 0/1"). Una vez procesado le indicamos a la IA los valores de los Weights y cuantas neuronas asignar (mas neuronas = mas tiempo para procesar). Poco a poco veremos cómo evoluciona su rendimiento, y nos animaron a trastear con estos valores y ver cómo afectan a la evolución del modelo predictivo.

Ya nos quedaba poco tiempo pero vimos [cnn](files/cnn.ipynb), dando imágenes de números a nuestro programa para que sea capaz de leerlos con una precisión correcta (con los parámetros base llega a una precisión del 99%).