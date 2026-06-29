# 🤖 Surveillance Bot – Mobile Controlled Surveillance Robot Using ESP32

A Bluetooth-controlled surveillance robot built using ESP32, L298N Motor Driver, and DC Motors. The robot can be controlled wirelessly through the Dabble mobile application, allowing safe monitoring and navigation in hazardous or inaccessible environments.

---

## 📖 Project Overview

Robotics plays an important role in reducing human effort and improving safety in dangerous environments. The Surveillance Bot is designed to perform remote movement operations using wireless communication between a smartphone and an ESP32 microcontroller.

The robot receives movement commands from the Dabble mobile application via Bluetooth and executes them through a motor driver module connected to four DC motors.

This project demonstrates the practical implementation of:

* Embedded Systems
* Robotics
* Bluetooth Communication
* Motor Control Systems
* Mobile-Based Robot Navigation

---

## 🎯 Problem Statement

In military zones, disaster-affected regions, industrial plants, and hazardous environments, direct human monitoring can be dangerous.

Challenges include:

* Risk to human life
* Inaccessible locations
* Need for remote surveillance
* Requirement for low-cost monitoring systems

---

## 💡 Proposed Solution

The Surveillance Bot provides a wireless and cost-effective solution for remote monitoring.

### Key Features

* Bluetooth-based wireless control
* Smartphone operation using Dabble App
* Four-wheel drive movement
* Real-time response
* Low-cost implementation
* Portable battery-powered design
* Expandable architecture for future upgrades

---

## ⚙️ System Architecture

```text
Smartphone (Dabble App)
            │
            ▼
Bluetooth Communication
            │
            ▼
ESP32 Microcontroller
            │
            ▼
L298N Motor Driver
            │
            ▼
4 DC Motors
            │
            ▼
Robot Movement
```

---

## 🔧 Hardware Components

| Component                  | Description                        |
| -------------------------- | ---------------------------------- |
| ESP32 Development Board    | Main controller                    |
| L298N Motor Driver         | Controls motor direction and speed |
| 4 DC Motors                | Robot movement                     |
| Robot Chassis              | Mechanical frame                   |
| Wheels                     | Locomotion                         |
| Lithium-Ion Battery        | Power source                       |
| Connecting Wires           | Circuit connections                |
| Smartphone with Dabble App | Remote controller                  |

---

## 🛠️ Software Requirements

* Arduino IDE
* ESP32 Board Package
* Dabble ESP32 Library
* Dabble Mobile Application

---

## 📲 Working Principle

### Step 1: Command Input

The user sends movement commands from the Dabble application.

Supported Commands:

* Forward
* Backward
* Left
* Right
* Stop

### Step 2: Bluetooth Communication

The command is transmitted wirelessly to the ESP32 using Bluetooth.

### Step 3: Command Processing

The ESP32 receives and processes the command.

### Step 4: Motor Control

The ESP32 sends signals to the L298N Motor Driver.

### Step 5: Robot Movement

The motor driver powers the motors according to the received command.

---

## 🚗 Robot Movements

| Command  | Action     |
| -------- | ---------- |
| Up       | Forward    |
| Down     | Backward   |
| Left     | Turn Left  |
| Right    | Turn Right |
| No Input | Stop       |

---

## 🔌 Wiring Connections

### ESP32 ↔ L298N

| ESP32 Pin | L298N Pin |
| --------- | --------- |
| GPIO 27   | IN1       |
| GPIO 26   | IN2       |
| GPIO 25   | IN3       |
| GPIO 33   | IN4       |
| GND       | GND       |

Motor A → Left Motors

Motor B → Right Motors

Power Source → Battery Pack

---

## 📁 Repository Structure

```text
Surveillance-Bot/
│
├── README.md
├── LICENSE
│
├── code/
│   └── SurveillanceBot.ino
│
├── hardware/
│   ├── Circuit_Diagram.png
│   ├── Wiring_Diagram.png
│
├── images/
│   ├── Robot.jpg
│   ├── Prototype.jpg
│
├── docs/
│   └── Project_Report.pdf
│
└── videos/
    └── Demo_Video_Link.txt
```

---

## 📸 Project Images

### Prototype

Add images here:

```markdown
![Prototype](images/Robot.jpg)
```

### Circuit Diagram

```markdown
![Circuit Diagram](hardware/Circuit_Diagram.png)
```

---

## 🎥 Demonstration

Add your demo video link:

```text
https://youtube.com/your-video-link
```

---

## 📊 Results

The robot was successfully tested and achieved:

* Stable Bluetooth communication
* Real-time response to commands
* Smooth directional movement
* Reliable operation within approximately 10 meters
* Portable and battery-powered functionality

---

## 🌍 Applications

* Military Surveillance
* Disaster Monitoring
* Industrial Inspection
* Hazardous Area Monitoring
* Educational Robotics
* Research and Development

---

## 🚀 Future Enhancements

* ESP32-CAM Live Video Streaming
* Obstacle Detection using Ultrasonic Sensor
* Wi-Fi Based Remote Control
* GPS Tracking
* Autonomous Navigation
* IoT Integration
* AI-Based Object Detection

---

## Advantages

✅ Low Cost

✅ Easy to Build

✅ Wireless Control

✅ Portable Design

✅ User-Friendly Operation

✅ Expandable Architecture

---

## 📚 References

1. ESP32 Technical Reference Manual
2. Arduino IDE Documentation
3. Random Nerd Tutorials
4. Circuit Digest ESP32 Projects
5. Electronics Hub ESP32 Robot Car
6. L298N Motor Driver Documentation

---

## 👨‍💻 Authors

* NITISH S


Department of Computer Science and Engineering

Tagore Engineering College

Anna University

2026

---

## 📄 License

This project is licensed under the MIT License.

Feel free to use, modify, and distribute this project for educational and research purposes.
