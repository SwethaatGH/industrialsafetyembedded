# Industrial Safety Monitoring System

## Video Drive Link : https://drive.google.com/file/d/1eCu-SYhrc498uGOFyV1ir-LN3STYyLBa/view?usp=sharing

## Introduction
Safety is a primary concern in industrial environments, where hazards such as fire outbreaks and electrical failures pose significant risks to workers and infrastructure. Monitoring environmental conditions in real-time is essential for early detection and proactive response to potential hazards. Therefore, there is a need for an innovative solution that seamlessly integrates sensor data collection, real-time analysis and remote monitoring capabilities to enhance safety protocols in industrial settings.

## Overview
### Sensors Used
- Temperature sensor
- Smoke detection sensor
- Voltage level sensor

### Communication Interface Used
- I2C

### Interface
- Web based user interface

## Installation
To install and set up the Industrial Safety Monitoring System, follow these instructions:

### Step 1: Hardware Setup
- Connect the sensors (DHT sensor for temperature and humidity, smoke sensor and voltage sensor) to the ESP32 microcontroller module according to the provided schematic diagram.
- Power up the ESP32 module and ensure all connections are secure.

### Step 2: Software Setup
- Clone or download the project repository to your local machine.
- Upload the provided code (`industry.ino`) to the ESP32 module using the Arduino IDE or another compatible development environment.

## Usage
Once the Industrial Safety Monitoring System is installed and configured, it will start monitoring environmental conditions in real-time. The OLED display will show the current sensor readings, and alerts will be triggered if any safety thresholds are exceeded. Additionally, users can access a web interface hosted by the ESP32 module to monitor sensor data remotely from any internet-enabled device.
Access the website by visiting IP ADDRESS "192.168.4.1" after connecting to "Fire Safety" using password "password"
