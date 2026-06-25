# Note 
This repository documents engineering work completed under a signed development agreement. The project was terminated before completion, and I currently have an unresolved payment dispute regarding compensation for a portion of the work performed with ***Heather*** and ***Craig***. This repository is intended to document my technical contributions and preserve a record of the engineering work I completed.

https://www.linkedin.com/in/heather-nehamen-16634512
https://m.yelp.com/biz/heather-nehamen-san-fernando-valley
https://www.instagram.com/p/CgxjO_EvwH4/

https://www.linkedin.com/in/craig-nehamen-4617279

<img width="1887" height="814" alt="3" src="https://github.com/user-attachments/assets/461964ed-835b-482a-9a26-e8a531c1101e" />
<img width="1629" height="539" alt="4" src="https://github.com/user-attachments/assets/242c8773-ce15-4fd1-939c-830ac4b63acd" />
<img width="1632" height="806" alt="5" src="https://github.com/user-attachments/assets/bfabcc78-6afb-472c-93d2-fa217921b5d5" />
<img width="1588" height="684" alt="6" src="https://github.com/user-attachments/assets/6fd2ac71-2532-4fa1-b9fc-52203d912040" />
<img width="1630" height="749" alt="7" src="https://github.com/user-attachments/assets/d8ff8949-18ee-430a-b48a-b9da9eed598b" />



# Baby Soothing Wearable Device (Embedded Systems MVP)

## Overview

This repository documents the development of an embedded wearable soothing device designed to provide gentle tactile vibration and calming audio for infants. The project focuses on creating a portable, battery-powered prototype capable of delivering natural-feeling soothing patterns while emphasizing low noise, low power consumption, safety, and future manufacturability.

The objective of this MVP was to validate the electromechanical architecture, embedded firmware, and hardware integration before moving toward a custom PCB and production-ready design.

---

# Project Objectives

* Develop a portable embedded soothing device
* Generate gentle vibration patterns using compact vibration motors
* Integrate soothing audio playback
* Minimize mechanical noise and resonance
* Optimize battery life and power consumption
* Create a modular architecture suitable for future manufacturing
* Validate mechanical and electrical integration

---

# Hardware Architecture

## Controller

* ESP32-S3 MCU
* USB programming interface
* GPIO expansion
* PWM motor control

## Motor System

* Multiple ERM vibration motors evaluated
* PWM-controlled motor driver (TB6612)
* Eccentric weight optimization
* Mechanical vibration characterization
* Noise and resonance optimization

## Sensors

* MPU6050 IMU
* Real-time vibration monitoring
* Motion characterization
* Vibration feedback analysis

## Audio System
* Embedded audio playback
* Speaker integration
* Volume control
* Simultaneous motor/audio operation
* Audio interference reduction

## User Interface

* Push buttons
* Debounce firmware
* Status LEDs
* Mode selection
* Speed selection

## Power System

* Rechargeable Li-ion battery
* Battery runtime estimation
* Current consumption analysis
* Power optimization

---

# Firmware Features

* PWM motor control
* Multiple vibration patterns
* Adjustable vibration intensity
* Button event handling
* Software debounce
* LED status management
* Audio playback control
* Simultaneous vibration and audio operation
* IMU data acquisition
* Vibration filtering
* Serial debugging
* Modular firmware architecture

---

# Mechanical Development

* Eccentric weight CAD design
* Motor mounting optimization
* Internal component packaging
* Enclosure integration
* Cable routing
* Mechanical balance optimization
* Vibration isolation concepts
* Noise reduction methods
* Prototype assembly support

---

# Engineering Activities

## Motor Evaluation

* Compared multiple vibration motors
* Measured vibration characteristics
* Evaluated current consumption
* Optimized vibration feel
* Selected final motor architecture

## Embedded Development

* ESP32 firmware development
* Peripheral integration
* Motor driver implementation
* Audio subsystem integration
* IMU integration
* Firmware debugging

## System Integration

* Combined motor and audio operation
* Electrical debugging
* Noise reduction
* Power optimization
* Hardware validation

---

# Prototype Validation

Testing included:

* Motor characterization
* PWM tuning
* Vibration pattern evaluation
* IMU vibration monitoring
* Audio quality testing
* Power measurements
* Simultaneous subsystem validation
* Mechanical stability
* Resonance reduction
* Functional prototype verification

---

# Future Development

* Custom PCB design
* Injection-molded enclosure
* Low-noise motor optimization
* Mobile application
* BLE connectivity
* Battery management optimization
* Production DFM
* Regulatory compliance
* Manufacturing validation

---

# Technologies

* ESP32-S3
* C/C++
* PlatformIO / Arduino Framework
* TB6612 Motor Driver
* MPU6050 IMU
* PWM Motor Control
* Embedded Audio
* CAD Mechanical Design
* 3D Printing
* Rapid Prototyping
* Embedded Systems
* Mechatronics

---

# Repository Purpose

This repository demonstrates the complete embedded systems engineering workflow for an electromechanical consumer prototype, including firmware development, hardware integration, mechanical design, system validation, and prototype optimization. The project emphasizes practical embedded product development from concept through functional MVP while considering manufacturability and future commercialization.
