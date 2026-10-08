# TechMesh Vital Monitoring and Ammo Tracking

ESP32-based real-time soldier monitoring and communication system using ESP-NOW mesh networking.

## 📌 Overview

TechMesh is an ESP32-based real-time soldier monitoring and communication system designed to monitor soldier health parameters, location, and emergency conditions.

The system uses ESP-NOW wireless communication to enable communication between multiple ESP32 nodes without depending on traditional Wi-Fi or Internet connectivity.

A Node.js and WebSocket-based server is used to provide real-time monitoring through a dashboard.

## 🎯 Objectives

- Monitor soldier vital parameters in real time.
- Track soldier location using GPS.
- Enable wireless communication between multiple soldier nodes.
- Provide emergency alert and notification functionality.
- Support multi-hop communication between nodes.
- Provide real-time monitoring through a dashboard.

## 🚀 Key Features

- ❤️ Heart rate monitoring
- 🫁 SpO2 monitoring
- 📍 GPS-based location tracking
- 📡 ESP-NOW wireless communication
- 🔗 Multi-hop mesh communication
- 🚨 Emergency alert mechanism
- ✅ Emergency alert acceptance
- 📶 RSSI-based distance estimation
- 📺 OLED-based local display
- 📳 Vibration-based alerts
- 🖥️ Real-time monitoring dashboard

## 🔧 Hardware Components

- ESP32
- MAX30105 sensor
- GPS module
- OLED display
- Vibration motor
- Push button
- Power supply

## 💻 Technologies Used

- Embedded C/C++
- ESP32
- ESP-NOW
- Arduino IDE
- Node.js
- WebSocket
- GPS
- MAX30105

## 🏗️ System Architecture

```text
                 Soldier Node 1
                       |
                       | ESP-NOW
                       ↓
                 Soldier Node 2
                       |
                       | ESP-NOW
                       ↓
                 Soldier Node 3
                       |
                       ↓
                Gateway / Server
                       |
                       | WebSocket
                       ↓
             Monitoring Dashboard
