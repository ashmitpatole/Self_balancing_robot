# Self Balancing Robot

This project involves the design and development of a two-wheeled self-balancing robot using feedback control. The robot maintains its balance using data from an IMU sensor and a PID control algorithm.

## Technologies Used
- Arduino
- IMU Sensor (Accelerometer + Gyroscope)
- PID Control
- Motor Driver
- Fusion 360

## Project Overview
The robot continuously measures its tilt angle using an IMU sensor. A PID control algorithm calculates the required motor response to maintain balance.

Motor speed and direction are dynamically adjusted to keep the robot upright.

## Key Components
- Microcontroller: Arduino
- Sensor: IMU (MPU6050 or similar)
- Motor Driver
- DC Motors
- Battery Power System

## Mechanical Design
The robot frame and component mounts were designed using Fusion 360 with focus on:

- Proper center of mass
- Structural stability
- Compact electronics placement

## Features
- Dynamic balance control
- Real-time feedback system
- Closed-loop control implementation

## Demonstration
(Add robot photos or video)

## Future Improvements
- Add Bluetooth control
- Implement ROS-based control
- Improve tuning of PID parameters
