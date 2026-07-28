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

- KiCad 9

---

## Repository Structure

Hardware/
KiCad project files

Documentation/
Schematics and PDFs

Manufacturing/
Gerbers, drill files, BOM, pick-and-place files

Images/
PCB renders and screenshots

---

## Images

### PCB

(Add image here)

### Schematic

(Add image here)

### 3D View

(Add image here)

---

## Manufacturing

Gerber files, drill files, and manufacturing outputs are provided in the Manufacturing folder.

---

## Project Status

Current Revision: A

Prototype

Hardware has not yet been manufactured or electrically validated.

---

## Future Improvements

- Replace AMS1117 with a low-dropout regulator
- Improve ground stitching
- Optimize routing
- Hardware validation
- Revision B

---

## License

MIT License
