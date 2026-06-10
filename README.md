# PID Motor Control and Monitoring
## Overview
This project implements a closed-loop PID position control system using Arduino, Python and an encoder. The system allows real-time tuning of PID gains through a custom Tkinter GUI while visualising system performance through live telemetry and plotting.

The project demonstrates embedded control, hardware-software integration, serial communication and real-time monitoring techniques commonly used in robotics and mechatronics applications.

## Hardware Used

- Arduino
- DC Motor
- Encoder
- Motor Driver
- External Power Supply

## System Architecture

Arduino:
- Reads encoder position
- Executes PID control loop
- Drives motor output
- Sends telemetry to Python

Python:
- Receives telemetry data
- Displays position and error
- Allows real-time PID tuning
- Plots system response

## Results

The controller successfully tracks user-defined position setpoints while allowing live adjustment of PID gains during operation. Position and tracking error are visualised in real time through the Python dashboard.


