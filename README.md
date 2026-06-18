# 🌱 Automatic Irrigation System using Arduino

An Arduino-based Automatic Irrigation System that monitors soil moisture levels and automatically controls a water pump to provide irrigation only when required. The project aims to reduce water wastage and automate the irrigation process with minimal human intervention.

---

## 📌 Overview

The system uses a Soil Moisture Sensor to continuously monitor the moisture content in the soil. The sensor readings are processed by the Arduino UNO. When the moisture level falls below a predefined threshold, the Arduino activates a Relay Module, which turns ON the water pump. Once the desired moisture level is reached, the pump is switched OFF automatically.

---

## 🚀 Features

- Automatic irrigation based on soil moisture levels
- Reduces water wastage
- Minimal human intervention
- Real-time moisture monitoring
- Simple and low-cost implementation
- Expandable for IoT and smart farming applications

---

## 🛠️ Components Used

| Component | Quantity |
|-----------|----------|
| Arduino UNO | 1 |
| Soil Moisture Sensor | 1 |
| Relay Module | 1 |
| Water Pump | 1 |
| Breadboard | 1 |
| Jumper Wires | As Required |
| Power Supply | 1 |

---

## ⚙️ Working Principle

1. The Soil Moisture Sensor measures the moisture content of the soil.
2. Arduino UNO reads the sensor values.
3. If soil moisture is below the threshold:
   - Relay is activated.
   - Water pump turns ON.
4. When sufficient moisture is detected:
   - Relay is deactivated.
   - Water pump turns OFF automatically.

---

## 📊 System Flow

```text
Soil Moisture Sensor
          ↓
     Arduino UNO
          ↓
     Relay Module
          ↓
      Water Pump
```

---

## 💡 Applications

- Smart Agriculture
- Home Gardens
- Greenhouses
- Water Conservation Systems
- Precision Farming

---

## 🔮 Future Improvements

- IoT Integration using ESP32
- Mobile App Monitoring
- Weather Forecast Integration
- Solar Powered Irrigation System
- Cloud Data Storage
- Multiple Soil Moisture Sensors

---

## 📚 Technologies Used

- Arduino UNO
- Arduino IDE
- Embedded C / Arduino C
- Soil Moisture Sensor
- Relay Module

---

## 🎯 Project Outcome

This project helped in understanding:

- Sensor Interfacing
- Embedded Programming
- Relay Control
- Automation Systems
- Basic Electronics and Circuit Design

---

## 👨‍💻 Author

**Yash Gundewadi**

B.Tech - Electronics & Computer Engineering  
MIT ADT University
