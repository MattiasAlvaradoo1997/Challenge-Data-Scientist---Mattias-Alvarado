# Challenge-Data-Scientist---Mattias-Alvarado
Para Latam Airlines


 Agradezco su consideración al comunicarse conmigo. Estas son las notas y/u observaciones al respecto:

- He implementado un nuevo modelo en python/keras mediante google collab para el preprocesamiento de datos. Los resultados fueron bastante parecidos a los modelos anteriores con su respectiva red entrenada (adjunto en el archivo .zip). 

- Para entender qué hice, primero escribí porciones de código para calcular la tasa de atraso según 7 variables de cada registro e implementé otro algoritmo de modo que, al momento de diseñar una api, se consideren strings como entradas a la red (para el caso de los días de la semana, nombres y periodos). Al entrenar la RNA, noté una precisión de la red que se mantenía bastante uniforme, incluso modificando los parámetros de entrenamiento. 

- La precisión se mantenía entre un 81% y 82% durante el entrenamiento. Al aumentar el número de capas ocultas de 2 a 12, la precisión incrementa ligeramente (a un 86% aprox) con el riesgo de someter a la red a un overfitting. 

- También noté una variación pobre en la base de datos, teniendo en cuenta el porcentaje de atrasos v/s no atrasos, lo cual puede ser una causa de la poca exactitud del sistema. Esto se ve en la matriz de confusión del archivo adjunto con el nuevo modelo, donde se toma una fracción de la BDD para ser analizada. 

- Otra solución sería cuantificar otras variables en el registro como la cola de pasajeros, retrasos anteriores (antes del vuelo en cuestión, durante el mismo día o lapso de tiempo), aviones entrantes v/s salientes, etc.
