# HuskyLens-AI

| Face Recognition  | Object Recognetion  | Tag Recognition  | Line Tracking
| ------------- | ------------- | ------------- | ------------- |
| <img width="294" alt="Screenshot 2024-07-30 222506" src="https://github.com/user-attachments/assets/48d8799e-2676-4333-8a07-a9583a663182"> | <img width="294" alt="Screenshot 2024-07-30 222506" src="https://github.com/user-attachments/assets/a478e287-e164-4ea1-b7c9-b509aafb00ea"> | <img width="294" alt="Screenshot 2024-07-30 222506" src="https://github.com/user-attachments/assets/c3c9b03b-954c-4bec-91ed-fd955fc643ac"> | <img width="294" alt="Screenshot 2024-07-30 222506" src="https://github.com/user-attachments/assets/a69e80da-cfc9-4329-8595-7906ba79c64b">



# HuskyLens Face Detection and LED Control

![husky](https://github.com/user-attachments/assets/cefb9b1d-9fa1-405d-8848-fd98f287ba11)


## Overview

This task demonstrates how to use the HuskyLens AI camera module to detect faces and control an LED based on the detection status. When a face is detected by the HuskyLens, the LED will turn on. If no face is detected, the LED will remain off.

## Components

- **HuskyLens AI Camera Module**: A camera module with built-in AI capabilities for object detection, face recognition, etc.
- **LED**: A light-emitting diode controlled by a microcontroller.
- **Microcontroller**: (e.g., Arduino, ESP32) to interface with HuskyLens and control the LED.
- **Power Supply**: To power the components.

## Installation

1. **Hardware Setup**:
   - Connect the HuskyLens to the microcontroller using the I2C interface
   - Connect the LED to a digital output pin on the microcontroller.
   - Ensure the power supply is properly connected.

2. **Software Setup**:
   - Install the necessary libraries for the HuskyLens and LED control in your development environment.
   - Upload the code to the microcontroller.
