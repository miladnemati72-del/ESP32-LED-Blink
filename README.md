# ESP32 LED Blinking Project

A simple beginner-friendly embedded systems project using ESP32 DevKit V1 and Arduino IDE.

## Project Overview

This project demonstrates how to control an LED using a digital GPIO pin on the ESP32 microcontroller.

The LED turns ON for one second and OFF for one second continuously.

## Hardware Requirements

- ESP32 DevKit V1
- LED
- 220Ω resistor
- Breadboard and jumper wires
- USB cable

## Circuit Connections

| ESP32 Pin | Connection |
|---|---|
| GPIO 2 | LED anode through 220Ω resistor |
| GND | LED cathode |

## Software

- Arduino IDE
- ESP32 Board Package
- Arduino C++

## Code

The project uses `pinMode()`, `digitalWrite()`, and `delay()` functions.

## Project Features

- GPIO output control
- LED ON/OFF switching
- 1-second timing interval
- Basic ESP32 programming

## Author

Milad Nemati

## License

This project is available for educational purposes.
