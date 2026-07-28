# ESP32-S3 Development Board

A custom ESP32-S3-WROOM-1 development board designed in KiCad.

## Overview

This project is a two-layer ESP32-S3 development board featuring USB Type-C connectivity, USB-to-UART programming, onboard 3.3 V regulation, and access to all ESP32-S3 GPIO pins.

The board was designed as a learning project to gain practical experience in professional PCB design using KiCad.

---

## Features

- ESP32-S3-WROOM-1 module
- USB Type-C connector
- CP2102N USB-to-UART bridge
- AMS1117-3.3 V voltage regulator
- Reset and Boot buttons
- All 40 ESP32-S3 pins exposed
- Two-layer PCB
- Ground plane
- Decoupling capacitors placed according to the reference design

---

## Main Components

| Component | Part Number |
|-----------|-------------|
| MCU | ESP32-S3-WROOM-1 |
| USB-UART | CP2102N |
| Voltage Regulator | AMS1117-3.3 |
| USB Connector | USB Type-C 16-Pin |

---

## Software

Designed using:

- KiCad 10.0.4

---

## Repository Structure

Hardware/
KiCad project files

Images/
PCB renders and screenshots

---

## Images

### PCB

<img width="616" height="873" alt="PCB" src="https://github.com/user-attachments/assets/771a7d42-6765-4e18-91d8-071b8237febf" />


### Schematic

<img width="1373" height="971" alt="Schematics" src="https://github.com/user-attachments/assets/1c8ae3eb-0d0b-46dd-a1a4-26ef1452381f" />


### 3D View

<img width="644" height="1068" alt="image" src="https://github.com/user-attachments/assets/13d3898f-5b9c-4a80-80bd-fd1943bc40fa" />



---

## Project Status

Current Revision: A

Prototype

**Hardware has not yet been manufactured or electrically validated.**

---

## Future Improvements

- Replace AMS1117 with a low-dropout regulator
- Improve ground stitching
- Optimize routing
- Hardware validation
- Revision B

---
## References

- Espressif ESP32-S3 Hardware Design Guidelines
- Espressif ESP32-S3-WROOM-1 Datasheet
- CP2102N Datasheet
- KiCad Official Libraries

## License

MIT License
