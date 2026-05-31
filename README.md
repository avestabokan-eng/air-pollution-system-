# air-pollution-system- 
# Air Monitoring System

## Overview

## This project presents an advanced IoT-based environmental monitoring system using the ESP32 microcontroller and multiple sensors to measure air quality, toxic gases, temperature, humidity, pressure, and noise levels in real time. This upgraded version of the system operates completely offline, with the ESP32 functioning simultaneously as a Wi-Fi Access Point and a local MQTT Broker (using PicoMQTT). The system processes mathematical data, handles sensor saturation through a Fail-Safe algorithm, and displays consolidated results on a 16x4 LCD. Furthermore, it provides physical alerts via RGB LEDs and a buzzer, while securely streaming live data to a mobile IoT dashboard for interactive monitoring.

## Team Members

* Avesta Hashim Abdullah
* Hamed Hassan Ali

## My Contributions

## Partner's Contributions

 wrote the code 

## Technologies Used

•

ESP32 Microcontroller (Acts as Node & Local Server)

MQ135 Sensor (General Air Quality)

•

MQ7 Sensor (Carbon Monoxide)

•

BME280 Sensor (Temperature, Humidity, Atmospheric Pressure)

•

Sound Sensor (Noise Level Measurement)

•

RGB LED & Active Buzzer

•

LCD Screen (16x4) with I2C Module

•

IoT MQTT Mobile Application (For dashboard visualization)

## Challenges Faced

One of the main challenges was ensuring accurate sensor readings and maintaining stable system performance. Multiple rounds of testing and debugging were required before obtaining reliable results.

## What I Learned

* Sensor integration and calibration
* System troubleshooting
* Team collaboration
* Project documentation and presentation

## Future Improvements

* Add wireless connectivity
* Improve data visualization
* Expand the range of monitored environmental factors
