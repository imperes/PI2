# Design

Nesta etapa foi pensado e planejado em um esquema elétrico e em seus respectivos componentes para compôr o circuito.

---
### Tabela de componentes 

Componente   | Quantidade
--------- | ------
LED | 10
Motor Servo MG995| 1
Módulo Buzzer 5V | 1
Sensor de Gás MQ2 | 1
Sensor de Movimento Presença PIR | 1
Resistor 330R | 10
Resistor 10K | 1
Arduino Mega 2560 | 1
Display LCD 16x2 |   1
Sensor de Temp. & Umi. DHT11 |   1
LDR | 1

---
### Maquete Eletrônica

Para a criação da maquete eletronica foi utilizado o software *Fritzing*. A partir dele foi criado o seguinte esquemático:

###### Figura 1 - Maquete eletrônica.
![Maquete Eletrônica](./Figuras/esquemacktcasa.jpg)

# Testes dos Componentes

Depois de definirmos os componenetes, é necessário entender o funcionamento e realizar os testes de cada item separadamente. 

A programação é realizada por meio da [IDE Arduino](https://www.arduino.cc/en/software) e antes de executar os códigos é preciso selecionar o modelo da placa que será utilizado, nesse caso Arduino Mega 2560. Nos links abaixo serão descritos como foi feito os testes de cada parte do projeto:

* [LEDs](./Testes/LEDs.md)
* [Motor Servo MG995](./Testes/servo.md)
* [Buzzer](./Testes/buzzer.md)
* [Sensor de temperatura e umidade DHT11](./Testes/DHT.md)
* [Sensor de luminosidade LDR](./Testes/LDR.md)
* [Sensor de presença PIR](./Testes/PIR.md)
* [Sensor de gás MQ2](./Testes/mq2.md)
* [LCD 16x2](./Testes/lcd.md)
