# ClimateWatch
𝗖𝗹𝗶𝗺𝗮𝘁𝗲W𝗮𝘁𝗰𝗵 es un modelo de clasificación basado en redes neuronales que detecta en tiempo real el estado del tiempo atmosférico a través de video. Cuenta con tres posibles clasificaciones respecto al tiempo atmosférico actual: 

▪️ Despejado: Representa la ausencia de lluvia y de nubes                                 
▪️ Nublado: Señala la presencia de nubes, con el fin de inferir la posibilidad de una pronta lluvia                       
▪️ Lluvia: Indica la presencia de lluvia

𝗢𝗯𝗷𝗲𝘁𝗶𝘃𝗼: ClimateWatch existe con el proposito principal de poder identificar el tiempo atmosférico con anticipación de un lugar al que deseamos visitar, para poder tomar desiciones sobre medio de transporte, vestimenta, entre otros, dependiendo si esta soleado, lloviendo o nublado.

En la version actual de este proyecto solo posee datos de entrenamiento de la carrera 10a con calle 13, Popayán, Cauca, Colombia, por ende solo puede hacer predicciones acertadas de este sector

𝗧𝗲𝗰𝗻𝗼𝗹𝗼𝗴í𝗮𝘀 𝘂𝘁𝗶𝗹𝗶𝘇𝗮𝗱𝗮𝘀:

🔸 Lenguaje de programación: Python              
🔸 Librerías principales: Numpy, Scikit-learn, Opencv           
🔸 Visualización de datos: Matplotlib                
🔸 Redes neuronales | Deep learning: TensorFlow, Keras

ClimateWatch cuenta con un dataset de 3 mil imagenes, repartidas de la sigueinte forma: mil imagenes de soleado, mil imagenes de lluvia y mil imagenes de nublado. Posteriormente para entrenar la red neuronal el grupo de divide en 1500 imagenes de entrenamiento, 750 imagenes de prueba y 750 imagenes de test, dando como resultado en el test un 100% de presición. 
