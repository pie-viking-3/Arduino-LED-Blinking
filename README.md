# Arduino-LED-Blinking

## Project Purpose
This project implements a basic LED blinking program using an Arduino Uno.

## Hardware Used
- Arduino Uno
- Built-in LED connected to digital pin 13

## Software Used
- Arduino IDE

## LED Pin Configuration
The LED is configured using digital pin 13.

The pin is set as an OUTPUT in the `setup()` function.

## Program Operation
The program continuously performs the following sequence:

1. Turn the LED ON.
2. Wait for 1 second.
3. Turn the LED OFF.
4. Wait for 1 second.
5. Repeat the process continuously.

## Blinking Interval
- LED ON time: 1 second
- LED OFF time: 1 second
- Delay used: `delay(1000)`

## Testing Status
The program was successfully compiled/verified in Arduino IDE using the Arduino Uno board configuration.

Physical hardware testing was not performed because a physical Arduino board was not available.

## QA Tracking
GitHub Issues were used to identify, review, document, and resolve QA-related issues in the project.
