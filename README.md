# G-Detector 
##G-Medidor de concentraciones de CO2, Metano, Azufre

##¿Cómo funciona? 
EL medidor de concentraciones funciona haciendo uso de una placa de desarrollo
 esp32 y un sensor MQ135. Para visualizar los datos utiliza  una app y firebase
 realtime.

##Equipo y material necesario
-> Sensor MQ135
El MQ-135 es un sensor de calidad del aire que permite detectar algunos gases peligrosos como Amoniaco, Dioxido de Nitrógeno, Alcohol, Benzeno, Dioxido y Monoxido de carbono. El sensor puede detectar concentraciones de gas entre 10 y 1000 ppm y es de utilidad para detección de gases nocivos para la salud en la industria principalmente. Su velocidad de respuesta es bastante buena, por lo que puede activar cualquier dispositivo de manera oportuna. La presentación es en un módulo que puede conectarse a un microcontrolador muy fácilmente y se incluye la electrónica básica para realizar la interfaz con el sensor, disponemos de salidas del tipo analógica y digital.

->Lecturas:
El sensor se alimenta con 5 volts
Rango de detección de Amoniaco: 10ppm-300ppm
Rango de detección Benceno: 10ppm-1000ppm
Rango de detección de Alcohol: 10ppm-300ppm

-> Esp32

-> Firebase Realtime
La conexión con Firebase Realtime, permite estar alamecenando las lecturas en tiempo real con el esp32 y con la app permite realizar laslecturas de dichos valores.
##

