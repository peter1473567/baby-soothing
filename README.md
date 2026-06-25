##Note 
This repository documents engineering work that I completed under a signed contract. The project ended before all completed work was compensated. I am publishing this repository to document my technical contributions and preserve a record of the development work I performed.


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
