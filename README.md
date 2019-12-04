# Murilo-Godoy
FATEC SANTO ANDRÉ
Mecatrônica Industrial

 Sistemas microprocessados e microcontrolados
Prof. Murilo Zanini de Carvalho

Samuel Alcantara Makoto Osuka         RA:0791811018
Murilo Petareli Godoy                 RA:0791811025


Relatório do Projeto: Controle de iluminação

Objetivo:
  Cotrole da iluminação de um cômodo com uma fita de leds(ou uma lampada) pelo usuário por meio remoto. O usuário possui controle total da iluminação por meio do aplicativo e pode ligar, desligar e variar o nível de iluminação dos LEDs. Caso desejar o projeto possui um controle automático usando um sensor LDR que irá ligar os LEDs conforme o nível de luminosidade cair.

Componentes utilizados:
•	Placa NodeMCU ESP8266;
•	Módulo Sensor de Luminosidade;
•	Módulo Ponte H L298n;
•	Matriz de Contatos;
•	Jumpers 
•	Fita de Led – 12V, 1A;
•	Fonte 12V.

![montagem final](https://raw.githubusercontent.com/murilogodoy/Murilo-Godoy/master/montagem%20final.jpeg)

Detalhes do projeto: 
Devido à baixa potência do NodeMCU, foi usado um Módulo Ponte H para elevar a tensão e a corrente necessária para acionar a fita de Led e realizar o controle da luminosidade com o auxílio do Módulo Sensor de Luminosidade, assim como descrito na proposta inicial.
Para fazer a comunicação com ESP8266 foi utilizado um código de exemplo da plataforma Blynk para a IDE do Arduino (disponível em: blynk.io) e alterado conforme as necessidades do projeto. 
Foi usado o aplicativo de celular “Blynk – IoT” para gerar o token e, assim, conectar-se ao servidor.

