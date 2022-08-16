# ESP32CAM_MQTT_JSON_DHT11

Este repositorio se enfoca en crear un programa para el micro controlador ESP32CAM en la IDE de Arduino que tenga las siguientes funciones:
- Leer el sensor de temperatura y humedad DHT11
- Haga una conexión a una red WiFi
- Haga una conexión a un broker local para mandar mensajes por MQTT
- Envie los datos obtenidos del sensor DHT11 en formato JSON

Utilizando Node Red se hará un dashboard que tendrá la siguiente inforamción y funciones:
- Graficará el valor actual de humedad relativa.
- Graficará en tiempo los valores de temperatura y humedad.
- Si la temperatura alcanza un valor X se encenderá el flashLed del microcontrolador.
