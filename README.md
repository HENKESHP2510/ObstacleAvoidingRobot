# ObstacleAvoidingRobot

Components used in this project:

Arduino Uno 
L293D Motor Driver Shield
Micro Servo 
Ultrasonic Sensor Module 
4 x Geared DC Motors & Wheels 
9-12V Battery Pack
A 9V block battery can’t usually produce enough current to drive the four motors. Rechargeable battery packs for RC cars tend to work best for this project.
8 x M3 x 15mm Socket Head Screws 
Ribbon Cable
Header Pins

Working:

The obstacle-avoiding robot uses an ultrasonic sensor mounted on a servo motor to continuously scan its surroundings. The sensor measures the distance to nearby objects, and the Arduino Uno processes this data to detect obstacles. Based on the distance, the Arduino controls the motors through the L293D motor driver to move forward, stop, or change direction. When an obstacle is detected, the servo rotates the sensor to check alternate paths, allowing the robot to navigate autonomously without collisions.
