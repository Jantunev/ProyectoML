# ProyectoML
Proyecto de curso Aprendizaje Automático

A continuacion se enumaran los pasos para desarrollar el codigo el cual se emplea para detectar a pacientes con cancer al pulmon usando el dataset que se puede descargar por medio del siguiente link:

https://drive.google.com/open?id=1RINTIrcQBbWBEfYkIeWiDBewsDDRwRqJ

https://drive.google.com/open?id=197f3hclLKde2AHT7e1CQ6XCGsrkfcrNx

1. Balancear la data:

1.1. Una vez descargados estos dos archivos se guardan en un carpeta de nombre 'data'
1.2. Paso siguiente es utilizar el siguiente codigo para balancear la data ya que esta contiene mucho negativos a comparación de los resultados positivos.  

Ejecutar el código: 1_1_Balanceo_Undersampling_OverSampling.ipynb

1.3. Este paso demora mucho debido a la cantidad de procesamiento, se adjunta un link para que pueda descargar la data ya balanceada:

https://drive.google.com/open?id=1MhSciEX3UP7sM6HqYZymlECm1uffjZcy

A coninuación se enumera los algortimos utilizados para obtener el mejor clasficación entre pacientes con o sin cancer. La eficacia de estos se determino utilizando la puntuación Kappa (Kappa Score) empleado para puntar clasficación de datos binarios.

2. Resultados empleando el algoritmo Random forest:

Ejecutar el código: 2_PruebasRandomForest_DataOriginal.ipynb

Mejor resultado usando kappa score = 

3. Resultados empleando el algoritmo Navie Bayes:

Ejecutar el código: 7_NaiveBayes.ipynb

Mejor resultado usando kappa score = 88.95% (Sin balancear la data 50.9%)

4. Resultados empleando el algoritmo Support Vector Machine:

Ejecutar el código: 6_SVM.ipynb

Mejor resultado usando kappa score = 98.62% (Sin balancear la data 80.06%)

5. Resultados empleando el algoritmo Support Vector Machine:

Ejecutar el código: 5_NeuronalNetwork.ipynb

Mejor resultado usando kappa score = 98.16% (Sin balancear la data 86.66%)

