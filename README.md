# Automated Box Sorting & Counting System

## Project Overview

A PLC-based automated box sorting and counting system developed using **Siemens TIA Portal** and **Factory I/O**.

The system detects and sorts boxes into **big and small categories** and maintains a separate count for each category.

## Objective

To develop an automated sorting and production-counting system using PLC logic, sensors, counters, and conveyor control.

## Technologies Used

* Siemens TIA Portal
* PLC Programming
* Ladder Logic (LAD)
* Factory I/O
* Sensors
* Counters
* Actuators
* Conveyor System
* Industrial Automation

## System Working

1. A box enters the conveyor system.
2. Sensors detect the incoming box and determine its size.
3. The PLC processes the sensor inputs.
4. The appropriate sorting mechanism directs the box to its designated location.
5. The corresponding counter is incremented.
6. Big and small boxes are counted separately.
7. The system continues operating while the production targets have not been reached.
8. When the **big-box counter reaches 10 AND the small-box counter reaches 10**, the conveyor automatically stops.

## Counting Logic

| Box Type  | Target Count |
| --------- | -----------: |
| Big Box   |           10 |
| Small Box |           10 |

The conveyor stops only when **both counters reach 10**.

## PLC Programming

The control logic was developed using **Ladder Logic in Siemens TIA Portal**.

The PLC program includes:

* Sensor input processing
* Box detection
* Size-based sorting
* Separate counters
* Counter comparison
* Conveyor control
* Conditional stopping logic

## Simulation

The PLC program was integrated with **Factory I/O** to simulate and test the complete sorting, counting, and conveyor-control process.

## Project Media

### Factory I/O Simulation

*Add your Factory I/O screenshot here.*

### PLC Program

*Add your TIA Portal Ladder Logic screenshot here.*

### Counter Logic

*Add a screenshot showing the counter logic here.*

### Project Demonstration

*Add your project demonstration video/link here.*

## Key Learning

This project helped me develop practical understanding of:

* PLC counters
* Sensor-based counting
* Ladder Logic
* Conditional logic
* Production quantity monitoring
* Conveyor control
* Industrial automation sequencing
* PLC simulation and troubleshooting

## Project Type

Automation / PLC Simulation Project
