RNN Bidirectional stacked (GRU) with mechanism attention

@autor: Jose Hugo Jaita Aguilar

wordsList.npy -> contiene las palabras del diccionario
wordVectors.npy -> contiene los word embedding de las palabras que conforman el diccionario

gen.ipynb  -> lee los xmls, y todo la data que contiene los reviews de movies, restaurantes, tweets, etc, luego genera las matrices que contiene los index del diccionario.
por ejemplo, el tweet "hola que tal, hola" se traduce en [32, 1005, 84, 32] en donde vienen hacer sus indices en el diccionario.

red.ipynb  -> Se construye la arquitectura de la red neuronal y se en entrena. 

test.ipynb -> Una vez entrenada se prueba la red neuronal.
 
