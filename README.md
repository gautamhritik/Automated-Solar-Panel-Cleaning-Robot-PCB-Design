# Automated Solar Panel Cleaning Robot – PCB Design

## Overview
This repository contains the custom PCB design for an Automated Solar Panel Cleaning Robot.  
The PCB integrates power management, motor interfacing, sensor inputs, communication protocols and system protection required for autonomous solar panel cleaning.

This project is intended for academic, prototyping, and learning purposes.

## Key Features
- Battery-powered operation with regulated outputs
- Buck converter for 5 V and 3.3 V rails
- Motor driver interface for the cleaning mechanism
- Sensor input support (0–3.3 V range)
- Power switch and LED status indication
- Reverse polarity, overcurrent, and transient protection
- Debug and expansion headers

## PCB Specifications
- Design Tool: KiCad
- PCB Layers: 2
- Input Power: Battery / External DC supply
- Logic Levels: 3.3 V, 5 V
- Design Status: Prototype (ERC & DRC verified)
- 
## Usage
1. Open schematic and PCB files using KiCad
2. Review power paths, connectors, and component ratings
3. Modify the design if required
4. Generate Gerber files for fabrication
5. Assemble and test the PCB

## Limitations
- Prototype and academic use only
- Not weatherproof or industrially certified
- Requires enclosure for real-world deployment

## Future Improvements
- EMI and noise optimization
- Battery monitoring and protection enhancement
- Waterproof connectors and enclosure
- Firmware-based diagnostics

## License
MIT License

## Author
Hritik Gautam
