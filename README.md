# PhysioTrack — IoT Health Monitoring System
A real-time health monitoring system integrating hardware sensors with a Python-based GUI, designed for personal and clinical use in homes, hostels, and rehabilitation centers.

## Overview
PhysioTrack connects a **MAX30100 pulse oximeter sensor** with a **Raspberry Pi** to continuously monitor vital signs and store health records securely. Built for students living away from home who need accessible, affordable health tracking.

## Features
- Real-time **heart rate** and **SpO2 (blood oxygen)** monitoring via MAX30100 sensor
- **BMI calculator** with health guidelines
- **Sleep data tracking** — manual entry through GUI
- Secure **user login** and health record storage via **MySQL**
- Python **Tkinter GUI** for easy interaction
- Optional **voice interaction** (Text-to-Speech + Speech-to-Text)
- Suitable for home, hostel, clinic, and rehabilitation center use

## System Architecture
```
MAX30100 Sensor → Raspberry Pi → Python GUI (Tkinter) → MySQL Database
                                        ↕
                              Voice I/O (TTS + STT)
```

## Tech Stack
- Python (Tkinter, pyttsx3, SpeechRecognition)
- Raspberry Pi
- MAX30100 Pulse Oximeter & Heart Rate Sensor
- MySQL
- RPi.GPIO

## Health Parameters Monitored
| Parameter | Method |
|---|---|
| Heart Rate | MAX30100 sensor via Raspberry Pi |
| SpO2 | MAX30100 sensor via Raspberry Pi |
| BMI | Calculated from user-entered height/weight |
| Sleep Duration | Manual entry via GUI |

## Future Improvements
- Web/mobile app for remote monitoring
- Emergency SMS alerts on abnormal readings
- ECG, blood pressure, glucose sensor support
- Cloud data storage and analytics dashboard
- Doctor notification system

## Use Cases
- Students living alone in hostels needing personal health tracking
- Home health monitoring for elderly or chronic condition patients
- Low-cost alternative to expensive clinical monitoring systems

## Author
Smarika Bhadauria — B.Tech Artificial Intelligence, MITS-DU Gwalior
