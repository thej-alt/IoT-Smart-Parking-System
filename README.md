# 🚗 IoT Smart Parking System

An IoT-based Smart Parking System developed using **ESP32**, **MQTT**, **Node-RED**, and **Ultrasonic Sensors** to provide real-time parking slot monitoring, automatic vehicle detection, environmental monitoring, and cloud dashboard visualization.

---

## 📖 Project Overview

The IoT Smart Parking System is designed to address the challenges of conventional parking systems by providing real-time parking slot availability. The system detects vehicle entry, exit, and slot occupancy using ultrasonic sensors. An ESP32 microcontroller processes the sensor data and publishes it through the MQTT protocol to a Node-RED dashboard for live monitoring.

Using cloud-based MQTT communication, the system enables remote monitoring from anywhere with an internet connection. Users can access real-time parking status, slot availability, vehicle count, temperature, and humidity through both the Node-RED dashboard and a mobile MQTT client.

Additionally, the system monitors environmental conditions using a DHT11 sensor and supports email alerts when the parking area becomes full. Its modular architecture ensures scalability, making it suitable for larger parking infrastructures and future smart city applications.

---

## ✨ Features

- Real-time parking slot monitoring
- Automatic vehicle entry and exit detection
- Live vehicle counting
- Parking slot occupancy detection
- MQTT-based communication
- Interactive Node-RED dashboard
- Remote monitoring from anywhere using cloud connectivity
- Mobile dashboard monitoring via MQTT client
- Temperature and humidity monitoring
- Email alert notification when parking is full
- Event-driven data transmission
- Low latency and reliable performance
- Scalable architecture for smart parking applications
---

## 🛠 Technologies Used

- ESP32
- MQTT Protocol
- Node-RED
- Arduino IDE
- Embedded C/C++
- Wi-Fi
- HC-SR04 Ultrasonic Sensor
- DHT11 Sensor

---

## 🔩 Hardware Components

- ESP32 Development Board
- HC-SR04 Ultrasonic Sensors
- DHT11 Temperature & Humidity Sensor
- LEDs
- Jumper Wires
- Breadboard
- Power Supply

---

## 💻 Software & Tools

- Arduino IDE
- Node-RED
- MQTT Broker
- Embedded C/C++

---

## 🏗 System Architecture

The system consists of four layers:

- Sensor Layer
- Processing Layer
- Communication Layer
- Visualization Layer

System flow:

Sensors → ESP32 → MQTT Broker → Node-RED Dashboard

---

## ⚙ Working Principle

1. Initialize ESP32 and sensors.
2. Detect vehicle entry and exit using ultrasonic sensors.
3. Update vehicle count.
4. Monitor individual parking slot occupancy.
5. Read temperature and humidity values.
6. Publish data to MQTT topics.
7. Node-RED subscribes to MQTT topics.
8. Dashboard updates in real time.
9. Email alerts are generated when the parking area becomes full.

---

## 📂 Repository Structure

```
IoT-Smart-Parking-System/
│
├── ESP32/
│   └── Smart_Parking_System.ino
│
├── NodeRED/
│   └── flows.json
│
├── Images/
│   ├── block_diagram.png
│   ├── system_architecture.png
│   ├── flowchart.png
│   ├── hardware_setup.png
│   └── dashboard.png
│   └── Mobile Monitoring using MQTT Application.png
│
├── Report/
│   └── Samsung_Innovation_Campus_Report.pdf
│
├── PPT/
│   └── Smart_Parking_Presentation.pptx
│
├── Demo/
│   └── README.md
│
└── README.md
```

---

## 📸 Project Images

The **Images** folder contains:

- Block Diagram
- System Architecture
- Flowchart
- Hardware Setup
- Node-RED Dashboard

---

## 🎥 Project Demo

Watch the demonstration video of the IoT Smart Parking System here:

**Google Drive:**  
(https://drive.google.com/file/d/1ECQRSfxGtpewxbas_RVnLIWCcolOnf3p/view?usp=sharing)

---

## 🚀 Future Enhancements

- Mobile application integration
- Cloud database support
- Multi-floor parking management
- Smart city integration
- Support for larger parking infrastructures by increasing the number of parking slots
---

## 👨‍💻 Author

**Regintala Krishna Teja**

B.Tech in Electronics and Communication Engineering

Indian Institute of Information Technology Design and Manufacturing (IIITDM), Kurnool

Email: krishnatej976@gmail.com

LinkedIn: https://www.linkedin.com/in/krishna-teja-r-291678290/

---

## ⭐ Acknowledgement

This project was developed during the **Samsung Innovation Campus (SIC) IoT Internship** as part of practical learning in Embedded Systems, IoT, MQTT communication, and Node-RED dashboard development.
