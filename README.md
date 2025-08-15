# RFID-Based-Smart-Parking-Management-System-using-8051-Microcontroller-with-Real-Time-Slot-Monitoring
An RFID-based parking management system using the 8051 microcontroller that verifies vehicle IDs, controls entry barriers, and tracks slot availability in real time via entry/exit sensors. A 16×2 LCD displays total, occupied, and available slots for efficient, secure parking.
# 8051 Smart Parking System

## Overview
This project implements a smart parking system using the 8051 microcontroller. It keeps track of cars entering and exiting a parking lot using push buttons (simulating entry/exit sensors). The current number of cars is displayed on an LCD. Entry and exit motors simulate gates.

## Features
- Car count tracking
- LCD display of parking status
- Entry and exit gates simulated with motors
- Easy-to-modify code for number of parking slots

## Proteus Simulation
- 8051 Microcontroller
- 16x4 LCD
- Push buttons for entry/exit
- DC motors for gates
- Virtual Terminal (optional, for debugging)
- [⚙️Proteus Project](Proteus/PARK.pdsprj) 

## Keil Code
- Written in C
- Compatible with AT89C51
- Delay functions, LCD control, motor control included
- [📄 Code File](Keil/8051.c)

## How to Run
1. Open the Proteus project (`PARK.pdsprj`)
2. Load the compiled HEX file from Keil
3. Press push buttons to simulate cars entering/exiting
4. Watch the LCD update the car count and motors simulate gate movement
