# Ficak (fičák) V1
Booster for T21 radiators.

## Introduction
As part of multiple energy saving activities in our house I did not find any "cool" solution for airflow booster attachable nicely to T21 radiators. And have to create one:

![ficak](pic/IMG_20220916_113225.jpg)

## 3D models
I created model of holder attachable into T21 radiators (only 66mm thick) and universal case for controller and 40mmx40mm fan.

![model](pic/IMG_20220915_125354.jpg)

It is possible to connect several fans in row only by adding another "fan" module - fan module is just paralel cable with fan and connectors.

### tinkercad models & STLs

[files](stl)


## Circuit Diagram

![schematics](conf/ficak-jidelna-wiring-schema.png)

NodeMCU VIN should handle up to 18V. I'm using 12V input voltage and <20dB fans.

### NodeMCU tasmota configuration

![tasmota](conf/ficak-jidelna-configure-module.png)


### HA overview

![tasmota](conf/ficak-jidelna-HA.png)


## Photos

![ficak](pic/IMG_20220915_125042.jpg)
![ficak](pic/IMG_20220915_125049.jpg)
![ficak](pic/IMG_20220915_125354.jpg)
![ficak](pic/IMG_20220915_125513.jpg)
![ficak](pic/IMG_20220915_165905.jpg)
![ficak](pic/IMG_20220915_202426.jpg)
![ficak](pic/IMG_20220915_202434.jpg)
![ficak](pic/IMG_20220915_202439.jpg)
![ficak](pic/IMG_20220916_000941.jpg)
![ficak](pic/IMG_20220916_100747.jpg)
![ficak](pic/IMG_20220916_100855.jpg)
![ficak](pic/IMG_20220916_100905.jpg)
![ficak](pic/IMG_20220916_101416.jpg)
![ficak](pic/IMG_20220916_101422.jpg)
![ficak](pic/IMG_20220916_110906.jpg)
![ficak](pic/IMG_20220916_113225.jpg)

## Measurements

TBD - I will do some measurements and whole family subjective assessment during heating season ;-)
