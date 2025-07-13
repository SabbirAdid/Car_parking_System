# Car_parking_System
Operating System Project Tools

# Car Parking Management System 🚗🅿️

## Project Overview
This project involves the development of an **Arduino-based Car Parking System** using an I2C LCD display and ultrasonic sensors. The system aims to simplify parking management, help drivers find parking spots quickly, and optimize space usage in parking lots.

The project includes both hardware (Arduino, sensors, and LCD) and software components (Arduino code and system design). This system can be implemented in public and private parking lots to improve overall urban mobility.

---

## 📝 Table of Contents
1. [Introduction](#introduction)
2. [Objective & Methodology](#objective--methodology)
3. [Components](#components)
4. [System Design](#system-design)
5. [Installation](#installation)
6. [Results](#results)
7. [References](#references)

---

## 💡 Introduction
With the increasing number of vehicles in urban areas, managing parking spaces has become a critical issue. This system uses **Arduino** along with an **I2C LCD module** and **ultrasonic sensors** to create an intelligent parking solution. It provides real-time data on available parking spots to assist drivers in finding free spaces quickly.

### Key Benefits:
- **🚗 Efficient Parking Management**: Reduce the time spent looking for parking.
- **🅿️ Optimal Space Utilization**: Maximize the usage of available parking spaces.
- **💲 Cost-Effective Solution**: Use of affordable hardware like Arduino and LCD modules.

---

## 🎯 Objective & Methodology
### Objectives:
- **📍 Real-time Availability**: Display parking spot status on an LCD.
- **🔄 Optimized Space Distribution**: Ensuring effective use of available spots.
- **👨‍👩‍👧‍👦 User-Friendly Interface**: Easy-to-understand system for drivers.
- **💰 Cost-Efficiency**: Simple and affordable system setup.

### Methodology:
- **📡 Ultrasonic Sensors** measure the distance to the car and check if the spot is occupied.
- **🖥️ I2C LCD Display** shows whether a parking spot is available or not.
- **🔧 Arduino** processes the sensor data and controls the LCD display.

---

## 🔧 Components
- **💡 Arduino Nano**: The brain of the system.
- **📺 I2C LCD Display (20x4)**: Shows parking availability.
- **🔉 Ultrasonic Sensors (x8)**: Detect car presence.
- **🔩 Mini Servo Motor (SG-90)**: Helps move barriers or gates if needed.
- **🔋 Power Supply**: 5V DC power adapter and 9V battery.
- **⚙️ Other components**: Jumper wires, IR Sensors, Capacitors, Voltage Regulator.

---

## 🖥️ System Design
### Hardware Architecture:
The system integrates:
- **Arduino Nano** connected to an **Ultrasonic Sensor** to measure parking spot occupancy.
- The data is sent to the **I2C LCD**, which displays available parking spots.

### Software Architecture:
The Arduino code reads sensor data, processes it, and updates the LCD to indicate the parking spot's status.

### System Flow:
1. **📏 Sensor Input**: Ultrasonic sensor measures distance.
2. **⚙️ Processing**: Arduino compares distance to determine occupancy.
3. **📱 Display Output**: Information is shown on the LCD.

![System Design](https://via.placeholder.com/500x300?text=System+Design)

---

## 📦 Installation

### Prerequisites:
1. **🖥️ Arduino IDE**: Install [Arduino IDE](https://www.arduino.cc/en/software) to upload the code.
2. **📚 Libraries**: Install necessary libraries like `Wire.h` and `LiquidCrystal_I2C`.

### Steps:
1. Connect the **Arduino Nano** to your PC.
2. Upload the provided **Arduino Code** to the Arduino.
3. Connect the **I2C LCD** and **Ultrasonic Sensors** to the Arduino as per the wiring diagram.
4. Power the system with a **5V adapter** or **9V battery**.

---

## 🏆 Results

The system works efficiently, displaying parking availability in real-time on the LCD screen. The ultrasonic sensors accurately detect parking spot occupancy, making the system ideal for both public and private parking lots.

---

## 📚 References:
1. J. Zhang, H. Chen, and X. Wang, "An Intelligent Car Parking System Based on Internet of Things," 2017.
2. A. Kumar, S. V. Pandey, and R. Garg, "Smart Parking System using IoT and Cloud Computing," 2018.
3. M. S. Chowdhury, M. Rahman, "Design and Implementation of a Smart Car Parking System Using Arduino and IoT," 2020.

---

### 📍 License
This project is open-source and available under the [MIT License](LICENSE).

---

## Stickers & Visuals 🎨
![Car Sticker](https://via.placeholder.com/150x150?text=Parking+System)
![Car Parking](https://via.placeholder.com/150x150?text=Car+Parked)
