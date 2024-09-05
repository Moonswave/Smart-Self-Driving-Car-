# Smart-Self-Driving-Car-

This project demonstrates an autonomous car capable of detecting and avoiding obstacles using ultrasonic sensors and motor control.

## Features

- **Ultrasonic Sensing**
  - Accurately detects obstacles up to 20 cm away with ±1 cm precision using the NewPing library.

- **Motor Control**
  - Controls wheel speed and direction with a 250 and 45 duty cycle, allowing for precise 1-second maneuvers.

- **Autonomous Navigation**
  - Processes sensor data every 100 ms, resulting in a reaction time of less than 1 second for turning and movement adjustments.

## How it Works

The system uses an ultrasonic sensor to detect nearby obstacles and adjusts the car's movements accordingly. By processing the sensor data in real-time and dynamically adjusting motor controls, the car navigates autonomously through its environment, avoiding collisions.
