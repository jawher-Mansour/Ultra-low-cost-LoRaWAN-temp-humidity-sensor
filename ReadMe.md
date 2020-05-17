# Low cost temp & humidty Sensor

This project is based on Atmega328 MCU,RF95W LoRa module and DHT-11 sensor 

* Based on LoRaWAN wireless technology
* Very long range up to several miles
* activation by personalization
* battery powred board  
* 8 MHz oscillator
* 868 MHz LoRa freq

![alt text](https://github.com/jawher-Mansour/pics/blob/master/Lora.jpg)
![alt text](https://github.com/jawher-Mansour/pics/blob/master/Lora2.jpg)

Schematic and pcb are available on demand

### Description

  The board mesures Temperature and humidity values and sends them throught LoRa wan module to The Thinges Network network server and then to cayenne my devices Server.

![alt text](https://github.com/jawher-Mansour/pics/blob/master/cay.png)
![alt text](https://github.com/jawher-Mansour/pics/blob/master/applicationsDataCayenneLPP.png)

### Requirements:

* Arduino IDE 
* require CayenneLPP.h,lmic.h , hal/hal.h and DHT.h librarys 
* need to configure NWKSKEY , APPSKEY and DEVADDR values from The Things Network server (application session key , network session key and device address)


![alt text](https://github.com/jawher-Mansour/pics/blob/master/The_Things_Network_device_overview_ABP.png)

