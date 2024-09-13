# Smart Home System using PIC18F4620

## Description
This project is a Smart Home System built for the PIC18F4620 microcontroller. It implements a software-layered architecture and includes modules for controlling home appliances using LEDs, GPIO management, and configuration of MCU settings. The project is designed to demonstrate embedded system concepts in a home automation context.

## Getting Started
To get started with this project, you will need:
- MPLAB X IDE for code development.
- XC8 Compiler for PIC18F4620.
- A PIC18F4620 microcontroller for hardware testing.
- MPLAB simulator for simulation testing.

## Folder Structure
## Software Architecture
This project follows a three-layered software architecture:
- **ECUAL (Electronic Control Unit Abstraction Layer):** This layer handles external components like LEDs.
- **MCAL (Microcontroller Abstraction Layer):** This layer includes low-level drivers, such as GPIO.
- **Application Layer:** This is the user-level interface that controls the system’s behavior, utilizing both MCAL and ECUAL.

## Modules
The key modules in this project are:
- **ECUAL_LED Module:** Controls the LEDs in the smart home system.
- **GPIO Module:** Manages the general-purpose input/output pins of the PIC18F4620.
- **Configuration Bits Module:** Sets up the microcontroller configuration bits required for the system to operate.

## Hardware Requirements
- PIC18F4620 microcontroller
- LEDs and Resistors
- Breadboard and Jumper Wires
- Power Supply
