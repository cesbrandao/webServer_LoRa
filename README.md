# webServer_LoRa

  Código adapatado de https://randomnerdtutorials.com/esp32-lora-sensor-web-server/ para o minicurso SBRT2020 "Novas plataformas de comunicação para Internet das Coisas - experiências e práticas", capítulo 3, tópico 3.4.2, página 89, em http://editora.ifpb.edu.br/index.php/ifpb/catalog/book/401.

  A prática propõe a construção de um sistema de monitoramento de sensores com um servidor Web. O sistema pode ser dividido em duas partes: o transmissor, composto por uma placa Heltec WiFi LoRa 32 (V2) e um módulo com sensor DHT11, utilizado para obter valores de temperatura e umidade do ambiente que serão enviados através do protocolo LoRaWAN para o receptor; e o receptor, outra placa, que recebe a mensagem e a exibe em uma página Web através de um servidor hospedado localmente na placa.

#### Esquemático do sistema proposto, com o pino de dados do módulo de sendor DHT11 conectado ao pino 13 da placa referente ao transmissor:

![esquematico1](https://github.com/cesbrandao/webServer_LoRa/blob/master/img/esquematico1.PNG)

#### O diretório referente ao receptor deve estar organizado da seguinte forma:

![esquematico2](https://github.com/cesbrandao/webServer_LoRa/blob/master/img/esquematico2.PNG)
