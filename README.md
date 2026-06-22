# Arduino Radar System using HC-SR04 & Servo Motor

## 📌 Overview

This project demonstrates a real-time Arduino Radar System using an Arduino Nano, HC-SR04 Ultrasonic Sensor, and SG90 Servo Motor. The servo rotates the ultrasonic sensor from 0° to 180°, scanning the surrounding area for objects. The measured distance and angle are sent to Processing through serial communication, where they are displayed as a live radar animation.

---

## ✨ Features

- Real-time radar visualization
- Object detection using HC-SR04
- 0°–180° servo scanning
- Live distance measurement
- Processing graphical interface
- Beginner-friendly project

---

## 🛠️ Components Required

- Arduino Nano
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor
- Breadboard
- Jumper Wires
- USB Cable

---

## 🔌 Circuit Connections

### HC-SR04 Ultrasonic Sensor

| HC-SR04 Pin | Arduino Nano |
|--------------|--------------|
| VCC | 5V |
| GND | GND |
| TRIG | D10 |
| ECHO | D11 |

### SG90 Servo Motor

| Servo Pin | Arduino Nano |
|------------|--------------|
| VCC | 5V |
| GND | GND |
| Signal | D12 |

> Note: If you change the wiring, update the pin numbers in the Arduino code.

---

## 💻 Software Used

- Arduino IDE
- Processing IDE
- Processing Serial Library

---

## 📂 Project Structure

Arduino-Radar-System/
│
├── Arduino_Code/
│   └── Radar.ino
│
├── Processing_Code/
│   └── Radar_Display.pde
│
├── Images/
│   ├── circuit.jpg
│   └── radar_demo.png
│
├── LICENSE
└── README.md

---

## 🚀 How to Run

1. Open `Radar.ino` in Arduino IDE.
2. Select Arduino Nano and the correct COM Port.
3. Upload the code.
4. Open `Radar_Display.pde` in Processing IDE.
5. Select the same COM Port.
6. Click **Run**.
7. Move an object in front of the sensor to see the live radar animation.

---

## 📸 Output

- Real-time radar scanning
- Angle display
- Distance display
- Object detection

---

## 📚 Technologies Used

- Arduino Nano
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor
- C/C++
- Processing
- Serial Communication

---
## 🎥 Demo Video

[![Arduino Radar System Demo](https://img.youtube.com/vi/5MCcgJNIzIQ/maxresdefault.jpg)](https://www.youtube.com/shorts/5MCcgJNIzIQ)


https://www.youtube.com/shorts/5MCcgJNIzIQ

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project helpful, please ⭐ Star this repository and follow for more Arduino, ESP32, and Electronics projects.

**Made with ❤️ by TSAR ELECTRONICS**
