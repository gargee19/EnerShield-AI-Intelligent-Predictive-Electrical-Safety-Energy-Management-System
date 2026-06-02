# EnerShield AI

An AI-powered electrical safety and energy management system that combines real-time monitoring, predictive fault detection, and automated protection to improve electrical reliability and energy efficiency.

## Overview

EnerShield AI monitors voltage, current, temperature, and vibration data using sensors connected to an ESP32 microcontroller. The collected data is analyzed using an LSTM-based machine learning model to identify anomalies and predict potential electrical faults before they become critical.

When unsafe conditions are detected, the system can automatically trigger protective actions, generate alerts, and provide real-time monitoring through a web dashboard.

## Features

* Real-time electrical parameter monitoring
* Predictive fault detection using LSTM
* Dynamic risk assessment
* Automated relay-based protection
* OLED status display
* Audio alert system
* Web-based monitoring dashboard
* IoT-enabled remote access

## Hardware Components

* ESP32
* ACS712 Current Sensor
* ZMPT101B Voltage Sensor
* DS18B20 Temperature Sensor
* SW-420 Vibration Sensor
* Relay Module
* OLED Display
* Audio Module / Buzzer

## Software Stack

* Python
* Arduino IDE
* TensorFlow / Keras
* FastAPI
* WebSocket
* HTML, CSS, JavaScript

## System Workflow

Sensors → ESP32 → AI Analysis → Risk Assessment → Protection & Alerts → Dashboard

## Future Enhancements

* Cloud-based analytics
* Mobile application support
* TinyML deployment
* Smart grid integration
* Renewable energy monitoring

## License

This project was developed for research, innovation, and hackathon purposes.
