# Temperature Monitoring System

*Company*: CODTECH IT SOLUTIONS

*Name*: Bushra Khanum

*Intern ID*: CT04DK44

*Domain*: Embedded System

*Duration*: 4 Weeks

*Mentor*: Neela Santhosh Kumar

This project is a beginner-friendly implementation of a Temperature Monitoring System using an Arduino microcontroller and a temperature sensor (e.g., LM35 or DHT11). The system reads real-time temperature values and displays them via the Serial Monitor. It serves as an excellent introduction to sensor interfacing, analog-to-digital conversion, and serial communication in embedded systems.

# Project Overview

The main objective of this project is to continuously monitor ambient temperature and display the readings in real time. The Arduino reads the analog/digital signal from the temperature sensor, converts it into temperature values in Celsius, and prints the results on the Serial Monitor. This setup can be used for applications like environmental monitoring, smart thermostats, or industrial temperature tracking.

# Components Used

Arduino UNO

Temperature Sensor

16x2 LCD Display

# Working Principle
The sensor detects the surrounding temperature. The result is printed on the LCD Display at regular intervals. The system can be extended to display values on an LCD.

# Key Features

Real-time temperature monitoring

Easy-to-understand analog/digital sensor interfacing

Output via LCD

Scalable for use in larger environmental monitoring systems

# Code Functionality

The code initializes the sensor and sets up serial communication. In the loop, it continuously reads sensor data, converts it to temperature in Celsius, and prints it to the Serial Monitor. A delay ensures readings are spaced at regular intervals.

# Applications

Home or industrial temperature monitoring

Educational projects for learning sensor interfacing

Base for IoT-based smart temperature systems

Agriculture and greenhouse environment tracking

# Future Enhancements
Add an LCD or OLED display for independent monitoring

Include humidity measurement (if using DHT11)

Send data wirelessly using Wi-Fi (ESP32) or Bluetooth

Set threshold alerts with buzzer or LED indicators

Data logging to SD card or cloud for analysis


