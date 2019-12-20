# Máquina Enigma Beta N1
Proyecto de la materia Telemática III

Máquina enigma con dos rotores

# Materiales

3 Servomotores

Regulardor 5v (LM7805)

Raspberry Pi 3 B+

Jumpers

Protoboard

3 Resistencias (330 Ω/0.25W)

27 Leds

Alimentador de 12V


# Tutorial

https://www.youtube.com/watch?v=kkEfIszVuvA&feature=youtu.be

# Descripción General

A continuación se detalla el diseño y la construcción de una maquina enigma de dos rotores por medio de un sistema embebido y servomotores, se detalla el método para obtener la adecuada calibración de estos implementos y se postulan mejores futuras para su implementación.

# Servomotores
Para trabajar adecuadamente con servomotores es necesario establecer el rango de operación y las características mecánica de cada elemento, por tanto se sugiere previo a la construcción de la máquina, se experimente con ellos para determinar cuanto puede girar cada uno y que tanto error acumulado tienen entre el rango de operación, en el código descrito en este proyecto se establecen estrategias para reducir el comportamiento errático de algunos servomotores, sin embargo el comportamiento cambia según el fabricante y características propias del elemento por tanto se siguiere compensar y modificar estos valores para un óptimo rendimiento.

#Raspberry pi 
El código planteado esta elaborado en Python 3, por tanto es recomendable que al usar la Raspberry pi se actualice, para la ejecución fue necesario la correcta ubicación de cada pin GPIO con la numeración de la board, es recomendable cambiarlos a un nomenclatura normal si esta acostumbrado a esta, 

# Leds
Para la visualización de la salida de la maquina se utilizaron 26 leds difusos conectados directamente al sistema embebido, para una siguiente entrega se recomienda un sistema matricial de led para obtener mejores resultados con menos pines usados.


