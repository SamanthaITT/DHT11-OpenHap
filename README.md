# DHT11-OpenHap
Este repositorio tiene el código para hacer lectura con el sensor DHT, enviar la información al canal y posteriormente desplegar el dato en OpenHap.

Si se quiere probar manualmente la conexión entre mosquitto y el openhap, se puede utilizar el sigueinte comando en terminal: 

mosquitto_pub -h localhost -p 1883 -q 0 -t codigoIoT/G6/temp -m 25

La configuración general del openhap es la siguiente:

![Screenshot from 2022-06-17 19-25-53](https://user-images.githubusercontent.com/96089257/174419055-9f1a0403-5e21-441f-83f3-c7e6e6034c1b.png)
