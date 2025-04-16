# Arduino Autonomous Defense System 🔧🛡️

An **autonomous object-detection defense system** built using Arduino. It simulates a radar turret that scans the environment, detects nearby objects, and reacts with **visual and auditory alarms**.

The system also features a **real-time radar interface** on the Arduino IDE Serial Monitor, showing live angle and distance feedback when an object is detected.

---

## 📦 Features

- 🧠 **Autonomous scanning** via servo + ultrasonic sensor
- 🎯 **Object detection** with distance threshold logic
- 🚨 **Buzzer + laser alarm** when objects are within range
- 🕹️ **Manual/Auto toggle** using joystick clicks
- 📟 **LCD feedback** showing system status
- 📡 **Live radar view** through "Processing" software for real-time feedback 

---

## 🧰 Hardware Used

- Arduino Uno R4 WiFi
- HC-SR04 ultrasonic sensor
- SG90 servo motor x2
- Joystick module
- LCD (I2C)
- Passive buzzer
- Laser diode or LED
- Breadboard + jumper wires
- 5V USB or external power

---

## 🚀 How It Works

1. In **automated mode**, the servo rotates to scan surroundings.
2. If an object is detected within range:
   - The system stops scanning
   - Rotates toward the object
   - Triggers the buzzer and laser
   - Displays a warning on the LCD
   - **Serial output updates with object angle + distance, which then updates on Processing with real-time radar detection** 
3. When the object is gone, it resumes scanning.
4. Joystick:
   - Single click → manual mode
   - Double click → return to auto mode

---

## 📸 Demo / Media
https://youtu.be/RGREBWFjeFs

---

## 👤 Author

Phong Ngo – Mechatronics Engineering Student | [LinkedIn](https://linkedin.com/in/phong-duong-ngo-36a6502b3)


---
