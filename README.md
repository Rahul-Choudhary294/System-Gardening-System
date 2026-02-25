🌱 Smart Gardening System Using ESP32 & Blynk IoT
📌 Project Overview

The Smart Gardening System is an IoT-based automated plant care solution designed to monitor soil moisture and pH levels in real time. Using the ESP32 microcontroller and Blynk IoT platform, the system automatically controls water pumps to maintain optimal soil conditions while allowing remote monitoring and manual control through a smartphone.

This project helps reduce water wastage, minimizes manual effort, and promotes healthy plant growth through smart automation.

🚀 Features

✅ Automatic watering based on soil moisture level

✅ pH-based soil condition monitoring and correction

✅ Real-time IoT monitoring using Blynk app

✅ Manual & Automatic operation modes

✅ Remote pump control from smartphone

✅ Low-cost and scalable design

🛠️ Hardware Components

ESP32 Development Board

Soil Moisture Sensor

pH Sensor Module

2-Channel Relay Module

2 × DC Water Pumps

External Power Supply (5V/12V)

Breadboard & Jumper Wires

💻 Software Requirements

Arduino IDE

ESP32 Board Manager

Blynk IoT Application

Wi-Fi Network

⚙️ System Working

ESP32 reads soil moisture and pH sensor values.

If moisture < 50%, Pump 1 turns ON (automatic irrigation).

If pH ≥ 8, Pump 2 turns ON (soil correction).

Data is sent to the Blynk cloud.

Users can monitor values and manually control pumps via the Blynk app.

📲 Blynk Dashboard Widgets

Moisture Gauge (V1)

pH Gauge (V2)

Pump 1 Status (V3)

Pump 2 Status (V4)

Manual Pump 1 Control (V5)

Manual Pump 2 Control (V6)

Auto/Manual Mode Switch (V7)

🔌 Pin Configuration
Component	ESP32 Pin
Moisture Sensor	GPIO 34
pH Sensor	GPIO 35
Relay IN1 (Pump 1)	GPIO 26
Relay IN2 (Pump 2)	GPIO 27
🌍 Applications

Home Gardening

Greenhouses

Agriculture Fields

Nurseries

Smart Farming Systems

✅ Advantages

Saves water

Reduces manual work

Real-time monitoring

Cost-effective solution

Improves plant health

🔮 Future Enhancements

Add Temperature & Humidity Sensor (DHT11/DHT22)

NPK Sensor for nutrient monitoring

Solar-powered system

AI-based watering prediction

Web-based dashboard
