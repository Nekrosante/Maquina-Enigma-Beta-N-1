# Máquina Enigma Beta N1
Proyecto de la materia Telemática III

Máquina enigma con dos rotores

# Materiales

3 Servomotores

Regulardor 5v (LM7805)

Raspberry Pi 3 B+

Jumpers

Protoboard

3 Resistencias (330 ohms/0.25W)

27 Leds

Alimentador de 12V


# Tutorial

https://www.youtube.com/watch?v=kkEfIszVuvA&feature=youtu.be

# Descrpcion General

A contiuacion se detalla el diseño y la consrucion de una mauqina engima de dos rotores por medio de un sistma enbebdio y servomotores, se detalla el metodo para obtener la adecuada calibracion de estos implemento y se postulan mejors futuras para su implemenacion

# Servmotores
Para trabajar adecuadamente con servmomotres es necesario establcer el rango de operacion y cracteristicas mecanica de cada elemento, por tanto se sugiere previo a la construcion de lamauina se experiemnte con ellos para determianr cuanto puede girar cada uno y que tanto error acumulado tienen entre el rango de operacion, en el codigo descrito en este proyecto se estbalcen estrategias para reducir el comportaiemnto erratico de algunos servomotores,sin emabrgo el comprotacinto cambia egun el fabricante y caracteristivcas propias del elemnto por tanto se suguiere conpensar estos valores para un optimo rendimiento

# raspberry pi 
EL codigo planteado esta elaborado en python 3, por tanto es recomendable que al usar la raspberry pi se actualize, para la ejecuacnion fue ncesario la correcta ubicacion de cada pin GPIO a utlizar.

# Leds


