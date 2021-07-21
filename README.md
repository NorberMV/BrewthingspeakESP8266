# Retrieving and dysplay temperature Data from a Brew Process using ESP8266 module and two DS18B20 sensors.


## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
*IoT for the ESP8266 Wi-Fi microchip, here I work with the WeMos D1 mini specially,
*Need to include the library secrets.h and modified it with the local network and Thigspeaks API key
*information.
The ThigspeakMultipleFields.ino code, have been modified from official ThingSpeak Copyright 2018, The MathWorks, Inc. to read two sensors DS18B20 from the Mash tank and the cooling process and sends the data to a specific channel in Thingspeak in simultaneus fields.
Public Alpha IoT channel: https://thingspeak.com/channels/878882
	
## Technologies
Project is created with:
* Lorem version: 12.3
* Ipsum version: 2.33
* Ament library version: 999
	
## Setup
To run this project, install it locally using npm:

```
$ cd ../lorem
$ npm install
$ npm start
```
