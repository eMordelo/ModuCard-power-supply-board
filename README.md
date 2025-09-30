# ModuCard Base Module

This repository provides a  design for power module in the ModuCard system. This module is designed to seamlessly interface with the [ModuCard backplane](https://github.com/KoNarRobotics/ModuCard-backplane), powering a modular and expandable robotics platform.
<img width="892" height="866" alt="obraz" src="https://github.com/user-attachments/assets/4fe4b4e2-b66e-4fa1-9448-aba6cc8a598c" />


## Used tools:
<img align="center" height="64" src="img/logos/KiCad.png">

## Features:

### Power section
- **Input voltage:** 65÷36V from the battery connection.
- **Output voltage:** ADR, 12V and 5V standby lines, drivable form MCU.

### ST-LINK
- Built-in **ST-LINK** connected to the backplane via USB interface.  
- Enables programming and debugging of the onboard MCU.

### CAN interface
- Two independent CAN buses: **CAN1** and **CAN2**.  
- Both connect with the backplane to facilitate communication between the onboard MCU and other modules in the system.
