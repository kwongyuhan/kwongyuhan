# STM32 Chess Piece Recognition and Automatic Grasping System

An embedded vision and motion-control project for chess piece recognition and automatic grasping.

## Overview

This project was developed for the Beijing Undergraduate Electronic Design Contest. The system uses STM32 as the main controller, OpenMV for visual recognition and coordinate localization, and stepper motors for automatic grasping.

## My Role

Team leader

## My Contributions

- Built the main control architecture based on STM32.
- Used RTOS to support multi-task scheduling.
- Integrated OpenMV for black/white chess piece color classification and coordinate localization.
- Controlled stepper motors to complete automatic grasping.
- Led team coordination during the contest and system debugging.

## System Architecture

```text
OpenMV Camera
    |
    v
Color Classification + Coordinate Localization
    |
    v
STM32 Main Controller
    |
    v
RTOS Task Scheduling
    |
    v
Stepper Motor Driver
    |
    v
Automatic Chess Piece Grasping
```

## Tech Stack

- STM32
- RTOS
- OpenMV
- Stepper motor control
- Embedded C
- Mechanical structure debugging

## Award

Third Prize, Beijing Undergraduate Electronic Design Contest

## Future Improvements

- Improve localization robustness under varying lighting conditions.
- Add trajectory planning for smoother grasping.
- Add a calibration module for camera-to-actuator coordinate mapping.

