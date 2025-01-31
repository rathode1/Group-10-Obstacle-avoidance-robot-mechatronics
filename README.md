Obstacle Avoidance Robot

Introduction

This project is an Obstacle Avoidance Robot built using an Arduino Uno. It uses three ultrasonic sensors to detect obstacles and navigates safely by controlling four DC motors via a motor driver. An LCD display shows sensor readings and system status, while a potentiometer (Pot-HG) allows for speed adjustments.

Components Required

Microcontroller:Arduino Uno

Sensors: 3x Ultrasonic sensors (HC-SR04)

Motor Driver: L293D

Motors: 4x Simple DC motors

Display: 16x2 LCD with I2C module

Other Components: Potentiometer (Pot-HG)


Working Principle

1. Ultrasonic sensors detect obstacles by measuring distance.


2. The Arduino Uno processes sensor data and makes movement decisions.


3. The motor driver (L293D) controls the four DC motors.


4. If an obstacle is detected, the robot changes direction accordingly.


5. The LCD displays distance readings and movement status.


6. The potentiometer adjusts the ultrasonic sensor sensitivity 



Circuit Connections

Arduino Uno Pin Configuration

Code Implementation

1. Initialize sensors, motors, LCD, and potentiometer in Arduino IDE.


2. Continuously read distance from ultrasonic sensors.


3. If an obstacle is detected, stop or change direction.


4. Adjust speed using the potentiometer.


5. Display real-time status on the LCD.



Installation and Usage

1. Assemble the hardware as per the circuit diagram.


2. Upload the Arduino code via the Arduino IDE.


3. Power the robot using a battery pack.


4. Adjust speed using the potentiometer.


5. Observe the movement and LCD readings.



Future Improvements

Adding more sensors for better navigation.

Implementing Bluetooth or Wi-Fi control.

Using a more efficient motor driver for smoother motion.

Implementation of Machine Learning to make the robot learn from past experiences 

License

This project is open-source. Feel free to modify and improve it.


