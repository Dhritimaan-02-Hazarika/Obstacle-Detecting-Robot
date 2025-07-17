🤖 Obstacle-Avoiding Robot with Ultrasonic Sensors (Arduino)
This project implements an autonomous obstacle-avoiding robot using an Arduino, ultrasonic sensors, and DC motors driven via an L298N motor driver. The robot can detect obstacles in front, left, and right directions and dynamically adjust its path by turning away from obstacles.

Project Features:-

Uses three ultrasonic sensors to measure distances in:

1.Front
2.Left
3.Right

Basic obstacle avoidance logic:-

1.Moves forward if the path is clear

2.If blocked, chooses to turn left or right based on which side has more clearance

3.Smooth motor control using PWM speed control

4.Compatible with common robotics kits using L298N motor drivers

Hardware Components:-

1.Arduino UNO (or compatible board)

2.3x HC-SR04 Ultrasonic Sensors

3.L298N Motor Driver

4.2x DC Motors (for movement)

5.Chassis, Wheels, and Battery Pack

6.Jumper wires


Behavior Logic:-
1.If front distance > 13 cm, robot moves forward.

2.If an obstacle is detected in front.Robot stops.Compares left and right distances.Turns in the direction with more space.Resumes movement.
