🤖 Obstacle-Avoiding Robot with Ultrasonic Sensors (Arduino)
This project implements an autonomous obstacle-avoiding robot using an Arduino, ultrasonic sensors, and DC motors driven via an L298N motor driver. The robot can detect obstacles in front, left, and right directions and dynamically adjust its path by turning away from obstacles.

Project Features
Uses three ultrasonic sensors to measure distances in:

Front

Left

Right

Basic obstacle avoidance logic:

Moves forward if the path is clear

If blocked, chooses to turn left or right based on which side has more clearance

Smooth motor control using PWM speed control

Compatible with common robotics kits using L298N motor drivers

Hardware Components
Arduino UNO (or compatible board)

3x HC-SR04 Ultrasonic Sensors

L298N Motor Driver

2x DC Motors (for movement)

Chassis, Wheels, and Battery Pack

Jumper wires


Behavior Logic
If front distance > 13 cm, robot moves forward.

If an obstacle is detected in front:

Robot stops.

Compares left and right distances.

Turns in the direction with more space.

Resumes movement.
