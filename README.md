# Ultrasonic-Radar
Ömür Atlıhan - 230202047
Murad Nasirov - 220202902


This project is an ultrasonic radar system that detects the distance and angle of surrounding objects and visualizes them live on a computer screen. The core hardware consists of a servo motor (SG90) with an ultrasonic sensor (US-025) mounted on top. As the motor continuously sweeps across a 180-degree area, the sensor measures the distance to nearby objects.

The angle and distance data are then processed by the microcontroller (Arduino Uno or PIC16F877A), which acts as the brain of the system, and instantly transmitted to the computer via the serial port. On the PC side, a custom MATLAB program reads this incoming data and draws a live, classic radar sweep on the screen. The project's software is built on an embedded system architecture designed to ensure that sensor reading, motor control, and serial communication all run smoothly and simultaneously without freezing or delaying one another.
