# 🚗 Automated Guided Vehicle (AGV)
### Line Following Navigation + WiFi Controlled Robot

## 📌 Project Overview
This project presents an Automated Guided Vehicle (AGV) capable of autonomous navigation using line-following technology and manual control through WiFi communication.

The robot follows predefined paths using infrared sensors and can also be remotely controlled via a web-based interface using the ESP8266 WiFi module.

---

## 🎯 Objectives
- Develop autonomous navigation using line tracking
- Enable wireless control via WiFi
- Combine automation and manual override
- Demonstrate smart industrial vehicle concept

---

## ⚙️ Features
✅ Line Following Navigation  
✅ WiFi Remote Control  
✅ Dual DC Motor Drive  
✅ Real-time Direction Control  
✅ Speed Adjustment  
✅ Autonomous + Manual Modes  

---

## 🧠 Working Principle

### 1️⃣ Line Following Mode
IR sensors detect black line contrast.
Motor speeds are adjusted based on sensor feedback to keep the robot aligned.

### 2️⃣ WiFi Control Mode
ESP8266 creates a WiFi Access Point.
User connects via phone and sends movement commands through browser interface.

---

## 🧩 Hardware Components
- ESP8266 NodeMCU
- L298N Motor Driver
- IR Sensor Array
- DC Motors with Wheels
- Breadboard
- Battery Supply
- Chassis

---

## 🔌 Circuit Diagram
![Circuit](circuit/circuit_diagram.png)

---

## 💻 Software Used
- Arduino IDE
- ESP8266 Board Package
- Embedded C Programming

---

## 📂 Project Structure