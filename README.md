# HELIX INTERACTIVE SERVICE ROBOT

## Overview
HELIX is an interactive embedded robotics prototype designed to combine autonomous interaction, motion control, and expressive visual feedback into a compact utility robot platform.

The system integrates wireless mobile control, obstacle interaction, servo-based automation, and animated OLED expressions to create a responsive robotic experience.

---

## Project Concept
HELIX was designed as a human-interactive robotic platform capable of:
- remote-controlled movement
- expressive visual behavior
- autonomous lid operation
- touch-based interaction

The robot combines utility-oriented behavior with personality-driven interface design.

---

## Key Features

### Mobile Controlled Movement
- Controlled wirelessly using Bluetooth
- Differential wheel drive system
- Arduino-based RC control architecture

### OLED Animated Eyes
- 0.96" OLED display used for robotic facial expressions
- Simulated emotional states

### Touch Interaction System
- Capacitive touch sensor triggers emotional response
- Eye animations switch into “happy mode”

### Autonomous Lid Mechanism
- Ultrasonic sensor detects nearby object/person
- Servo motor opens lid automatically
- Auto-close after delay cycle

### Dual Microcontroller Architecture
- Arduino UNO handles mobility system
- Arduino Nano manages UI and interaction system

---

## Hardware Components

### Main Controllers
- Arduino UNO
- Arduino Nano

### Motion System
- DC Gear Motors
- Motor Driver Module
- Wheels / Tire Assembly

### Sensors
- Ultrasonic Sensor (HC-SR04)
- Touch Sensor Module

### Output Devices
- OLED Display (SSD1306)
- Servo Motor
- Bluetooth Module (HC-05 / HC-06)

---

## System Behavior

### Movement Layer
Phone commands are sent via Bluetooth to Arduino UNO, controlling robot movement:
- Forward
- Backward
- Left
- Right
- Stop

---

### Interaction Layer
Arduino Nano controls:
- OLED eye animations
- Touch reactions
- Lid automation system

---

### Autonomous Lid Logic
1. Ultrasonic detects nearby user
2. Servo rotates to open lid
3. Delay timer starts
4. Lid closes automatically

---

## OLED Expression System
HELIX includes animated robotic eyes to simulate:
- Idle mode
- Happy mode
- Blink states
- Interaction feedback

---

## Engineering Highlights
- Modular embedded architecture
- Multi-controller communication concept
- Interactive robotics interface
- Human-robot interaction design

---

## Achievement
This project was presented at an engineering exhibition and achieved recognition among participating university-level engineering projects.

---

## Future Upgrades

### Phase 2
- Voice interaction system
- Rechargeable battery platform
- Autonomous navigation

### Phase 3
- AI-based interaction logic
- Face tracking camera
- Smart waste classification

### Phase 4
- SLAM navigation system
- Mobile app interface
- ROS-based architecture migration

---

## Status
Prototype Phase – Interactive Robotics Platform

