 Ultrasonic Blind Stick
An affordable, Arduino-based obstacle detection system designed to assist visually impaired individuals with navigation.
 What It Does
This project uses an ultrasonic sensor to detect objects in front of the user. When an object is detected within a certain distance (e.g., 100 cm), a buzzer activates to alert the user about a nearby obstacle.
 
 Components Used
 •	Arduino Uno
•	Ultrasonic Sensor (HC-SR04)
•	Buzzer
•	Jumper Wires
•	Breadboard
•	Power Supply (Battery or USB)

How It Works
1.	The ultrasonic sensor sends out ultrasonic pulses.
2.	It measures the time taken for the echo to return after hitting an obstacle.
3.	The Arduino calculates the distance based on the time delay.
4.	If the distance is less than 100 cm, it triggers the buzzer to warn the user.

Circuit Diagram
Connections:
•	HC-SR04 Trigger → Pin 9
•	HC-SR04 Echo → Pin 10
•	Buzzer → Pin 8
•	VCC/GND of all components → Arduino 5V/GND
Code
You can find the full code in the ultrasonic_blind_stick.ino file.


Future Improvements
•	Add vibration motor for silent feedback
•	Include a rechargeable battery pack
•	Make it wearable using a compact PCB

