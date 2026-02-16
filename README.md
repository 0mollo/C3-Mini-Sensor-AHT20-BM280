# C3-Mini-Sensor-AHT20+BMP280
![image alt](https://github.com/0mollo/C3-Mini-Sensor-AHT20-BM280/blob/main/PiggyBack%20front%20view.png) | ![image alt]()

Barometric Pressure & Temperature Sensor  
Part of the Carenuity Modular Hardware Ecosystem


## Overview

The Carenuity AHT20+BMP280 Piggyback Module is a compact I²C-based atmospheric pressure and temperature sensing board designed for seamless integration with Carenuity controller platforms.

This module is optimized for 5V system operation and is intended to be used with host boards that provide I²C pull-up resistors.


## Features

- Bosch BMP280 digital barometric pressure sensor
- I²C communication interface
- 5V system operation
- Compact piggyback form factor
- Designed for Carenuity modular ecosystem
- Mounting holes for mechanical stability


## Board Dimensions

- Width: 25.60 mm
- Height: 28.30 mm


## Electrical Characteristics

| Parameter | Value |
|------------|--------|
| Operating Voltage | 5V |
| Interface | I²C |
| Pull-up Resistors | Not included |
| Measured Parameters | Pressure, Temperature |



## Pinout

| Pin | Function |
|------|----------|
| VCC | 5V Supply |
| GND | Ground |
| SDA | I²C Data |
| SCL | I²C Clock |


## Intended Use

This board is designed as a piggyback module for:

- ESP32-based Carenuity controllers
- ESP8266 boards
- Arduino-compatible systems
- Custom Carenuity PCBs


## Example Applications

- Weather stations
- Altitude measurement systems
- Climate monitoring
- Indoor pressure logging
- IoT atmospheric sensing


## Firmware Library

Recommended Arduino library:

- Adafruit BMP280
- SparkFun BMP280


## License

MIT License

Copyright (c) Carenuity
