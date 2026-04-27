# 🔐 ESP32 Secure Room Monitoring System

> Embedded smart access control and environmental monitoring system using ESP32, RFID, Fingerprint Sensor, MQTT communication and Web Dashboard.

---

## 📌 Project Overview

This project was developed as an internship project at **Mobilis**.

The objective was to design a smart embedded system for securing technical rooms containing sensitive telecom equipment such as servers, routers, batteries and power systems.

The system combines:

- 🔒 Secure room access control  
- 🌡 Environmental monitoring  
- 🌐 Remote supervision dashboard  
- 📡 IoT communication protocols  

---

## 🚀 Main Features

### 🔐 Double Authentication Access

Access is granted only after successful verification of:

- Fingerprint authentication  
- RFID card validation  

### 🌡 Environmental Monitoring

Real-time monitoring of:

- Temperature  
- Humidity  

### 🌐 Web Dashboard

Remote dashboard allows:

- Live sensor values  
- Access history logs  
- Alerts monitoring  
- Device supervision  

### 💡 Remote Controls

- Fan control simulation  
- Lighting control simulation  

---

## 🛠 Hardware Components

- ESP32-WROOM-32  
- RC522 RFID Reader  
- Fingerprint Sensor  
- LCD 16x2 I2C  
- DHT11 Sensor  
- LEDs  
- Push Button  
- Breadboard + Jumper Wires  

---

## 💻 Software & Tools

- Arduino IDE  
- Visual Studio Code  
- KiCad  
- MQTT Mosquitto Broker  
- HTML / CSS / JavaScript  

---

## 🔌 Communication Protocols

| Protocol | Usage |
|---------|------|
| UART | Fingerprint Sensor |
| SPI | RFID Reader |
| I2C | LCD Display |
| HTTP | Web Dashboard |
| MQTT | Remote Monitoring |
| NTP | Date & Time Sync |

---

## ⚙️ System Workflow

1. User places finger on sensor  
2. Fingerprint is verified  
3. User scans RFID card  
4. If both valid → Door access granted  
5. Event logged with timestamp  
6. Temperature & humidity monitored continuously  
7. Alerts generated when abnormal values detected  

---

## 📷 Project Preview

### Prototype
![Prototype](images/prototype.jpg)

### Web Dashboard
![Dashboard](images/dashboard.png)

### Circuit Design
![Circuit](images/circuit.png)

---

## 📈 Future Improvements

- Fire / Smoke detection  
- GSM alert notifications  
- Battery voltage monitoring  
- Automatic generator control  
- Cloud dashboard integration  
- Mobile application  

---

## 🎯 Skills Demonstrated

- Embedded Systems Design  
- ESP32 Programming  
- Sensor Integration  
- Communication Protocols  
- IoT Systems  
- Security Systems  
- Debugging & Testing  
- Web Interface Development  

---

## 👩‍💻 Author

**Keltoum Larbaoui**  
Electrical Engineering Student  
Passionate about Embedded Systems, Automation and Smart Technologies.

---
