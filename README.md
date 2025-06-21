# IOT_Projects
# WebX Servo Disco System with Ultrasonic Monitor

This project combines an ultrasonic distance sensor and a servo-controlled disco lighting system using an ESP32. It also sends real-time sensor data to the web (via Blynk, ThingSpeak, or custom dashboard).



##  Features

- Real-time distance monitoring using Ultrasonic Sensor (HC-SR04)
- Servo motor rotates when an object is detected
- Disco-style LED lighting effect
- Optional web integration for distance display and remote control

---

##  Components Used
----------------------------------------------------------
| Component            | Description                      |
|----------------------|----------------------------------|
| ESP32                | Main microcontroller with Wi-Fi  |
| Ultrasonic Sensor    | HC-SR04 for distance detection   |
| Servo Motor (SG90)   | Controls movement of lights      |
| LED Lights           | For disco effects                |
| Resistors            | For LEDs                         |
| Breadboard & Wires   | Prototyping                      |

---

## 🖼️ Circuit Diagram

(https://drive.google.com/file/d/1ESzTTfhEBLlzUaQSR2RyCXQ-mNvSSYpo/view?usp=drive_link)

---

## 🔌 Circuit Connections (ESP32)

| Component       | ESP32 Pin |
|----------------|-----------|
| Ultrasonic TRIG | D5        |
| Ultrasonic ECHO | D18       |
| Servo Motor     | D19       |
| LED 1           | D21       |
| LED 2           | D22       |
| LED 3           | D23       |





## 📷 Demo-video

https://drive.google.com/file/d/1a-E-jbRA16JOYRDdZXTDaV5Tux6A_p2G/view?usp=sharing


