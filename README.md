# Retrieving and Dysplaying temperature Data from a Brew Process using the API from thingspeaks + ESP8266 module and two DS18B20 sensors.


## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Pictures](#Pictures)

## General info
This is the first version of the Brew System for Alpha Brewery and we need to retrieve the temperature data from the two main 50 Liters tanks ( The boiler tank and the mash tank where crushed grains are mixed with water to form a porridge-like mixture called the “mash”. I used and modified the ThigspeakMultipleFields.ino example code, from official ThingSpeak Copyright 2018, The MathWorks, Inc.
In order to retrieve this temperature data an IoT system was implemented using the ESP8266 Wi-Fi module(here I work with the WeMos D1 mini.), and two DS18B20 digital temperature sensors sends the data to a specific two different channels in Thingspeak in simultaneus fields.
###Public Alpha IoT channel: https://thingspeak.com/channels/878882

The ThigspeakMultipleFields.ino code, have been modified from official ThingSpeak Copyright 2018, The MathWorks, Inc. to read two sensors DS18B20 from the Mash tank and the cooling process and sends the data to a specific channel in Thingspeak in simultaneus fields.

	
## Technologies
Project is created with:
* 1 Wemos D1 mini ESP8266 module
* 2 DS18B20 digital temperature sensors with a Inox 304 Stainless Steel probe

	
## Setup
To run this project, install it locally using npm:

```
$ cd ../lorem
$ npm install
$ npm start
```

## Pictures

<img src="https://github.com/NorberMV/BrewthingspeakESP8266/blob/master/temperatureData.jpg" width="100">
