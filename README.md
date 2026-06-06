# 🤖 Autonomous Obstacle Avoiding Robot

An Arduino-based Autonomous Obstacle Avoiding Robot developed to demonstrate obstacle detection, autonomous navigation, sensor integration, and embedded control systems.

This project utilizes ultrasonic sensing technology and intelligent motion control to detect obstacles in real-time and automatically select an alternate path without human intervention.

## 📖 Project Overview

The Autonomous Obstacle Avoiding Robot is designed to navigate independently while avoiding collisions with surrounding objects. The robot continuously measures the distance of nearby obstacles using an HC-SR04 ultrasonic sensor and adjusts its movement accordingly.

The project provides practical exposure to:

* Robotics Engineering
* Embedded Systems
* Sensor Integration
* Autonomous Navigation
* Motion Control Systems
* Arduino Programming


## ✨ Key Features

* 🤖 Autonomous navigation
* 📡 Real-time obstacle detection
* 🔄 Automatic path correction
* ⚙️ Arduino-based control system
* 📏 Ultrasonic distance measurement
* 🚗 Differential drive robot mechanism
* 🔋 Portable battery-powered operation


## 🛠️ Components Used

| Component                  | Purpose                |
| -------------------------- | ---------------------- |
| Arduino UNO                | Main controller        |
| HC-SR04 Ultrasonic Sensor  | Distance measurement   |
| L293D / L298N Motor Driver | Motor control          |
| DC Gear Motors             | Robot movement         |
| Robot Chassis              | Mechanical structure   |
| Wheels                     | Mobility               |
| Battery Pack               | Power supply           |
| Connecting Wires           | Electrical connections |


## ⚙️ Working Principle

### 1️⃣ Obstacle Detection

The HC-SR04 ultrasonic sensor continuously emits ultrasonic waves and receives the reflected signals from nearby objects.

The Arduino calculates the distance using the received echo signal.


### 2️⃣ Autonomous Navigation

When an obstacle is detected within a predefined distance range:

* The robot stops.
* The Arduino processes sensor data.
* The robot changes its direction.
* A new path is selected automatically.

This enables collision-free movement without human intervention.


## 🔄 System Architecture

HC-SR04 Ultrasonic Sensor
             │
             ▼
        Arduino UNO
             │
             ▼
      Motor Driver
             │
      ┌──────┴──────┐
      ▼             ▼
 Left Motor    Right Motor
             │
             ▼
    Autonomous Movement


## 🎯 Applications

* Mobile Robotics
* Autonomous Navigation Systems
* Educational Robotics
* Industrial Automation Learning
* Obstacle Detection Systems
* Smart Vehicle Concepts
* Robotics Research Projects

## 📚 Learning Outcomes

Through this project, the following concepts were explored:

* Arduino Programming
* Embedded System Design
* Ultrasonic Sensor Interfacing
* Distance Measurement Techniques
* Motor Driver Control
* Autonomous Robot Development
* Robotics System Integration
* Problem Solving and Debugging

## 📸 Project Gallery

### Robot Prototype

![Robot Prototype](assets/robot.jpg)

### System Block Diagram

![Block Diagram](assets/block-diagram.png)


## 🔮 Future Improvements

* Bluetooth-Based Remote Control
* IoT Monitoring and Control
* AI-Based Navigation
* Computer Vision Integration
* Line Following Capability
* Autonomous Mapping and Path Planning
* Smartphone App Control

## 👨‍💻 Author

**Sohan Kumar**

* B.Tech Mechatronics Engineering Student
* Diploma in Electrical Engineering
* Chandigarh University

### Areas of Interest

* Robotics
* Industrial Automation
* PLC & SCADA
* Embedded Systems
* Artificial Intelligence
* Mechatronics Engineering

⭐ If you found this project interesting, consider giving the repository a star.