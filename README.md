# Obstacle Avoiding Robot 🤖

Arduino-based 4-wheel robot that avoids obstacles using:
- **Adafruit Motor Shield**
- **HC-SR04 Ultrasonic Sensor**
- **Servo Motor** (to rotate sensor left/right)

## Features
- Moves forward until an obstacle is detected within 15 cm
- Backs up, scans left and right, then turns toward the clearer path
- Uses `AFMotor`, `NewPing`, and `Servo` libraries

## Hardware Connections
- Ultrasonic Sensor:
  - TRIG → A0
  - ECHO → A1
- Servo → Pin 10
- DC Motors → Motor Shield terminals M1, M2, M3, M4

## Getting Started
1. Install Arduino IDE
2. Install required libraries:
   - [AFMotor](https://learn.adafruit.com/adafruit-motor-shield/library-install)
   - [NewPing](https://github.com/livetronic/Arduino-NewPing/)
   - [Servo](https://github.com/arduino-libraries/Servo.git)
3. Open `src/ObstacleAvoidingRobot.ino` in Arduino IDE
4. Select your board & port, then upload!
