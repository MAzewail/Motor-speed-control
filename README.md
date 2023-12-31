# Arduino Ultrasonic Sensor Motor Control

[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Arduino IDE](https://img.shields.io/badge/Arduino%20IDE-1.8.16-blue)](https://www.arduino.cc/en/software)
[![Platform](https://img.shields.io/badge/Platform-Arduino-brightgreen)](https://www.arduino.cc/)

This is an Arduino project that uses an ultrasonic sensor to control the speed of a motor based on the distance measured by the sensor. If the distance is less than 200 cm, the motor will start moving at 25% of its speed and the lower the distance, the higher the speed of the motor.

## Requirements

To build this project, you will need the following components:

- An Arduino board (e.g. Arduino Uno)
- An ultrasonic sensor (e.g. HC-SR04)
- A motor (e.g. DC motor)
- Jumper wires
- Breadboard
- Power source (e.g. 9V battery)

## Installation

1. Clone this repository to your computer.
2. Connect the ultrasonic sensor to the Arduino board. Connect the VCC pin to the 5V pin on the Arduino board, the GND pin to the GND pin, the TRIG pin to pin 12, and the ECHO pin to pin 11.
3. Connect the motor to the Arduino board. Connect the positive wire to a digital pin (e.g. pin 9) and the negative wire to the GND pin.
4. Connect the power source to the motor. Connect the positive wire to the motor and the negative wire to the GND pin.
5. Connect the Arduino board to your computer using a USB cable.
6. Open the `ultrasonic_motor_control.ino` file in the Arduino IDE.
7. Upload the code to the Arduino board.

## Usage

1. Power on the motor and the Arduino board.
2. Place an object in front of the ultrasonic sensor. The distance between the object and the sensor will be displayed on the serial monitor.
3. If the distance is less than 200 cm, the motor will start moving at 25% of its speed. The lower the distance, the higher the speed of the motor.
4. Move the object closer or further away from the sensor to change the speed of the motor.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
