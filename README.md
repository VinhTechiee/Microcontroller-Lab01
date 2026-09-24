# Microcontroller-Lab01: LED Animations

## Course Information

**Course:** Microprocessors-Microcontrollers (CO3009)  
**Laboratory:** Lab 01 - LED Animations  

## Overview

This repository contains the implementation of LED-based applications developed for the Microprocessors-Microcontrollers laboratory course.

The projects are implemented using the **STM32F103C6 microcontroller** with **STM32CubeIDE** as the development environment and **Proteus** as the simulation platform.

The laboratory focuses on GPIO programming, LED control techniques, traffic light systems, seven-segment display interfacing, and a twelve-LED analog clock implementation.

## Objectives

The main objectives of this laboratory are:

- Understanding GPIO configuration and control on the STM32F103C6 microcontroller.
- Implementing LED control applications using STM32 HAL libraries.
- Designing and simulating digital circuits using Proteus.
- Interfacing a seven-segment display with the microcontroller.
- Developing reusable functions for LED-based clock applications.

## Laboratory Exercises

### Exercise 1: Two LEDs

Implement basic GPIO output control by switching the states of two LEDs connected to the STM32 microcontroller.

### Exercise 2: Traffic Light

Develop a three-color traffic light system using red, yellow, and green LEDs with predefined timing sequences.

### Exercise 3: Four-Way Traffic Light

Extend the traffic light system to a four-way intersection using twelve LEDs. Each direction contains three LEDs representing red, yellow, and green signals.

### Exercise 4: Seven-Segment Display

Interface a common-anode seven-segment display with the STM32F103C6 and implement a function to display numerical values from 0 to 9.

### Exercise 5: Traffic Light Countdown

Integrate the seven-segment display into the traffic light system to display the remaining time of each traffic-light state.

### Exercise 6: LED Clock

Construct a twelve-position LED clock using LEDs connected from PA4 to PA15. The LEDs are tested sequentially to verify hardware connections.

### Exercise 7: clearAllClock Function

Implement a function to turn off all twelve LEDs of the LED clock system.

### Exercise 8: setNumberOnClock Function

Implement a function to activate a specific LED position corresponding to a clock number from 0 to 11.

### Exercise 9: clearNumberOnClock Function

Implement a function to deactivate a selected LED position in the clock system.

### Exercise 10: Analog Clock

Combine the previous functions to implement a simple analog clock using three LED positions to represent hour, minute, and second information.

## Development Environment

### Hardware

- STM32F103C6 Microcontroller

### Software Tools

- STM32CubeIDE
- Proteus Simulation Software
- STM32 HAL Library

## Repository Structure
```text

Microcontroller-Lab01
│
├── Exercise01
│ └── Two LEDs
│
├── Exercise02
│ └── Traffic Light
│
├── Exercise03
│ └── Four-Way Traffic Light
│
├── Exercise04
│ └── Seven-Segment Display
│
├── Exercise05
│ └── Traffic Light Countdown
│
└── Exercise06-10
└── LED Clock Implementation
```

## Simulation

All circuits are designed and tested using Proteus simulation.

Each exercise includes:
- STM32CubeIDE source code.
- Proteus schematic design.
- Simulation results.

## Author

**Le Hien Vinh**
