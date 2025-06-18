# Proximity Alert System (Arduino)

An Arduino-based proximity alert system that:
- Uses an HC-SR04 ultrasonic sensor to measure distance
- Displays the live distance on a 16x2 I2C LCD
- Activates a pulsing buzzer if an object is closer than 10 cm

## Features
- Real-time distance display on LCD
- Buzzer pulses as a proximity warning
- Ideal for collision detection, obstacle sensing, or entry alerts

## Components
- Arduino UNO
- HC-SR04 Ultrasonic Sensor
- 16x2 LCD (I2C)
- Buzzer
- Jumper wires, Breadboard

## Circuit Connections

| Component       | Arduino Pin |
|----------------|-------------|
| TRIG_PIN       | 3           |
| ECHO_PIN       | 2           |
| SDA            | A4          |
| SCL            | A5          |
| Buzzer (+)     | 7           |

## Circuit Diagram
![Circuit Diagram](Image/Proximity-Alert-System.png)

## Working Diagram
![Working Diagram](Image/Proximity-Alert-System-Working.png)


## Schematic View
![Schematic View](Image/Proximity-Alert-System.pdf)

---

> Created by Shreyash Shrishette
