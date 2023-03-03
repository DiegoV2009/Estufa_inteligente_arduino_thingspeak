# Estufa_inteligente_arduino_thingspeak
#####Descripción:
>  Simulación de una estufa inteligente que cuenta con sensores de temperatura, ultrasonido, de gas mq5 y dos actuadores leds (simulando la boquilla) y servomotor (simulando la perilla).

#####Funcionamiento:
> Se tiene un arduino uno wi-fi d1 el cúal hace la lectura de los sensores de temperatura, de gas y de presencia y esa lectura la envía a la nube en [thingspeak][thigspeak], con base a estos datos sensados decide si abrir o cerrar la perilla, además de encender los leds que representan la boquilla de la estufa, de este modo si el sensor de ultrasonido no detecta presencia de algún objeto (una olla), no permite encender la boquilla ni girar la perilla, el sensor de temperatura ayuda a tener un estimado de la temperatura de cocción de los alimentos y el sensor de gas mq5 nos ayuda a la seguridad de fugas de gas.



[thigspeak]: https://thingspeak.com/ "thingspeak"
