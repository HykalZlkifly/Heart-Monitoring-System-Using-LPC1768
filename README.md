# Heart-Monitoring-System-Using-LPC1768
# Overview

This project implements a real-time heart rate monitoring system using the LPC1768 microcontroller. The system measures heartbeats, calculates BPM (beats per minute), and provides visual and audible alerts for normal and abnormal heart rates.

# Objective

To develop a reliable heart monitoring system that continuously measures heart rate and alerts the user of abnormal conditions using LEDs and a buzzer.

# System Architecture

Control System: LPC1768 microcontroller (ARM Cortex-M3)

Sensors: Pulse Sensor Amped (analog) or MAX30102 (digital/I2C)

Actuators / Output Devices: Green LED, Red LED, Buzzer

Firmware / Software: Keil uVision (C programming)

# Key Features

Continuous real-time heart rate monitoring

LED indicators for normal and abnormal heart rates

Audible alerts via buzzer for abnormal readings

Modular and scalable design for additional features (e.g., display, logging)

# My Contributions

Developed firmware for LPC1768 microcontroller

Implemented ADC sampling and heartbeat peak detection

Controlled LEDs and buzzer based on BPM thresholds

Tested and optimized heart rate measurement accuracy

# Usage

Connect the heart rate sensor and output devices to the LPC1768 according to the wiring diagram.

Load the firmware using Keil uVision.

Place a finger on the sensor to start monitoring.

LEDs and buzzer will indicate the heart rate status in real time.

# Author

Haikal Zulkifli
