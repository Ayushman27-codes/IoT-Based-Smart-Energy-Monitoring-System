# IoT Based Smart Energy Monitoring System

## Overview

The IoT Based Smart Energy Monitoring System is designed to monitor electrical parameters such as voltage, temperature, and humidity in real time using the ESP8266 microcontroller. The system sends sensor data to  sensor hub and provides live monitoring through a web dashboard.

## Features

* Real-time monitoring of voltage, temperature, and humidity
* Live dashboard for data visualization
* ESP8266 Wi-Fi based communication
* Remote monitoring using ThingSpeak
* Relay control through dashboard
* Overload detection and safety monitoring
* Real-time serial logging and history tracking

## Technologies Used

* Python
* Flask
* HTML
* CSS
* ESP8266
* sensor hub
* IoT Sensors

## Hardware Components

* ESP8266 
* Voltage Sensor Module
* Humidity Sensor
* Relay Module
* LM2596 Module

## Software Requirements

* Python
* Arduino IDE
* VS Code
* Flask Library
* PySerial

## Project Architecture

1. Sensors collect real-time data.
2. ESP8266 processes sensor values.
3. Data is transmitted using Wi-Fi.
4. Flask server handles communication and dashboard.
5. Dashboard displays live readings and relay status.
6. ThingSpeak stores and visualizes cloud data.

## Dashboard Features

* Live sensor monitoring
* Voltage status indication
* Relay ON/OFF control
* Historical data visualization
* Real-time logs and alerts
* Offline detection system

## Future Improvements

* Mobile application integration
* Machine learning for energy prediction
* Smart grid integration
* Advanced security features
* Multi-node industrial monitoring

## Team Members

* Ayushman Kar
* Dipanjan Roy
* Partho Roy

## Setup Guide

1. Connect ESP8266 with sensor modules.
2. Run the Flask server.
3. Open the dashboard in browser.
4. Monitor live sensor data and control relay remotely.


