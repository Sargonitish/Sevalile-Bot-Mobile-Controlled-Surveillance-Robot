# Sevalile-Bot-Mobile-Controlled-Surveillance-Robot
A safe and remote-controlled system is required to reduce human risk and improve safety.

## Overview

Sevalile Bot is a mobile-controlled surveillance robot developed using the ESP32 microcontroller and Bluetooth communication technology. The robot can be remotely operated through a smartphone using the Dabble application, allowing safe monitoring in hazardous or inaccessible environments.

The project demonstrates the integration of robotics, embedded systems, motor control, and wireless communication.

---

## Problem Statement

Performing surveillance in military zones, disaster-affected areas, and hazardous environments can be dangerous for humans.

Challenges include:

* Risk to human life during monitoring operations
* Inaccessible or dangerous locations
* Need for remote observation and movement
* Requirement for a low-cost surveillance platform

---

## Proposed Solution

The Sevalile Bot is a Bluetooth-controlled robotic vehicle designed to perform remote surveillance tasks.

Features include:

* Wireless control using smartphone
* Bluetooth communication through ESP32
* Four-wheel drive movement
* Forward, backward, left, and right navigation
* Cost-effective and easy-to-build design

---

## System Architecture

Mobile Phone (Dabble App)

↓

Bluetooth Communication

↓

ESP32 Microcontroller

↓

Motor Driver Module (L298N)

↓

DC Motors

↓

Robot Movement

---

## Components Used

| Component                  | Purpose                |
| -------------------------- | ---------------------- |
| ESP32 Microcontroller      | Main controller        |
| L298N Motor Driver         | Controls motors        |
| 4 DC Motors                | Robot movement         |
| Robot Chassis              | Structural support     |
| Wheels                     | Locomotion             |
| Battery Pack               | Power supply           |
| Connecting Wires           | Electrical connections |
| Smartphone with Dabble App | Remote control         |

---

## Working Principle

1. User opens the Dabble application on a smartphone.
2. Smartphone connects to ESP32 via Bluetooth.
3. Movement commands are sent from the app.
4. ESP32 receives and processes commands.
5. Motor driver activates the motors accordingly.
6. Robot moves in the desired direction.

Supported Commands:

* Forward
* Backward
* Left
* Right
* Stop

---

## Applications

* Military surveillance
* Disaster management
* Search and rescue operations
* Hazardous environment monitoring
* Educational robotics projects
* Remote inspection tasks

---

## Advantages

* Low-cost implementation
* Wireless operation
* Easy to develop and maintain
* Portable and lightweight
* Safe monitoring of risky environments

---

## Future Enhancements

* Live camera streaming
* Obstacle detection sensors
* Autonomous navigation
* GPS tracking
* Internet-based remote control
* AI-powered object detection

---

## Conclusion

The Sevalile Bot demonstrates an effective implementation of a mobile-controlled surveillance robot using ESP32 and Bluetooth technology. The project serves as a foundation for advanced robotic systems and highlights the practical applications of wireless communication and embedded systems in surveillance and rescue operations.

---

## Authors

Your Name

Institution / Department

Year

---

## License

This project is licensed under the MIT License.
