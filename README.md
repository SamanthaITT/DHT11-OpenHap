# DHT11-OpenHap
Este repositorio tiene el código para hacer lectura con el sensor DHT, enviar la información al canal y posteriormente desplegar el dato en OpenHap.

Si se quiere probar manualmente la conexión entre mosquitto y el openhap, se puede utilizar el sigueinte comando en terminal: 

mosquitto_pub -h localhost -p 1883 -q 0 -t codigoIoT/G6/temp -m 25

La configuración general del openhap es la siguiente:

![Screenshot from 2022-06-17 19-25-53](https://user-images.githubusercontent.com/96089257/174419055-9f1a0403-5e21-441f-83f3-c7e6e6034c1b.png)

En las reglas se agregó el sigueinte programa con Blocky:

![844cfd62-f0d3-48ed-ae7b-3e7420b60f53](https://user-images.githubusercontent.com/96089257/174422427-1ec1b945-a32f-4b10-bc1c-ea96acc4f8d1.png)

el ejemplo de la conexión del circuito se presenta en la siguiente imagen: 
![Photo from Library](https://user-images.githubusercontent.com/96089257/174422374-6748fa16-a183-4dd7-b037-df54bc868ee9.jpg)

