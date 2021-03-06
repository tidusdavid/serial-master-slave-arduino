# serial-master-slave-arduino
Código de ejemplo en Arduino que permite recibir comandos por medio del puerto Serial y traducirlos a comandar actuadores o leer información de sensores y reenviarla por el mismo puerto Serial. A continuación se presenta la arquitectura utilizada:

![alt text](https://raw.githubusercontent.com/tidusdavid/serial-master-slave-arduino/master/recursos/arquitectura.png)

## Requisitos

* [Arduino UNO](http://www.arduino.org/products/boards/arduino-uno) or [Arduino Mega](https://www.arduino.cc/en/Main/arduinoBoardMega).
* [Arduino IDE 1.8.3 or higher](https://www.arduino.cc/en/Main/Software).

## Comandos Seriales

A continuación se muestran los comandos implementados en el ejemplo de Arduino para comandar actuadores y leer sensores:

### Actuadores
* A: Prende un LED ubicado en el pin digital 13.
* a: Apaga un LED ubicado en el pin digital 13.

### Sensores
* p: Lee el valor análogo del pin A0 y lo imprime de vuelta en el Serial
* r: Lee el valor análogo del pin A1 y lo imprime de vuelta en el Serial
