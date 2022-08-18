# ESP32CAM_MQTT_JSON_DHT11

Este repositorio se enfoca en crear un programa para el micro controlador ESP32CAM en la IDE de Arduino que tenga las siguientes funciones:
- Leer el sensor de temperatura y humedad DHT11
- Haga una conexión a una red WiFi
- Haga una conexión a un broker local para mandar mensajes por MQTT
- Envie los datos obtenidos del sensor DHT11 en formato JSON
- Se recibirán los datos por MQTT en el tema codigoIoT/ejemplo/mqtt
- Se publicarán los datos por MQTT en el tema codigoIoT/ejemplo/mqttin

Utilizando Node Red se hará un dashboard que tendrá la siguiente inforamción y funciones:
- Mostrará los valores instantáneos de temperatura y humedad, el ID y el estado del flashled.
- Graficará en tiempo los valores de temperatura y humedad.
- Si la temperatura sobrepasa un valor deseado, en mi caso personal serán > 25 °C, se encenderá el flashLed del microcontrolador.

## Configuración de nodos

![](https://github.com/Alejandro-Dom/ESP32CAM_MQTT_JSON_DHT11/blob/main/Flow_DHT11.png)

## Dashboard

![](https://github.com/Alejandro-Dom/ESP32CAM_MQTT_JSON_DHT11/blob/main/Dashboard_DHT11)

