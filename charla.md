Tras una introducción a la inteligencia artificial, el machine learning, deep learning... pasamos a la práctica.

Esto ha de hacerse en Google Colab, los archivos en /files

AI-HEART-DISEASE

Los datos de heart.csv son 918 lineas con 12 columnas de datos, que exploramos en la sección 4 y en adelante. Exploramos los datos basado en sexo, edad...
Para que sa más fácil para el machine learning tratamos de traducir los valores no numéricos (ej sexo pasa a sexm y sexf) a 1's y 0's (en el caso de chest pain types lo dividimos en 3 variables y ponemos 0/1 en cada uno si lo tiene o no)

Una vez procesados los datos pasamos a la seccion de AI, donde en el 6.1 "fit" significa entrenar. Vemos que tras entrenar, y con random forest, la máquina ha tenido un 0.88 de éxito 
NOTA: En el pynb original hay un error en el bloque 62 -> esto está arreglado en el subido:
import sklearn.tree as tree

En 6.2 DL, dense solo tiene valor de 1 para tener probabilidad
shape es el numero de variables
dense es el numero de neuronas
learn rate es cuánto actualiza los pesos
epoch la cantidad de entrenamientos, en esencia es t de tiempo
cada epoca que pasa valora si ha ido mejor o peor y reajusta los pesos

una vez entrenamos evaluamos con evaluate, en mi caso ha pasado a un 0.87; hay vveces que hay que entrenar más
con lineplot vemos cómo ha variado en el tiempo

7. Evaluacion
La matriz de confusión
primera fila: 127- 109 ha acertado, 18 ha falado
segunda fila: 149- 17 ha fallado, 132 ha acertado
8. Visualization
Ver qué variables afectan de verdad
9. A investigar por nuestra cuenta

CNN

Probar a modificar los layers y denses
