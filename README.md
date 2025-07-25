# automated-license-plate-gate-control
Automated gate control system using license plate recognition with Raspberry Pi and Arduino

## Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [Hardware](#hardware)  
- [Setup](#setup)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)  

## Overview

A fully automated gate that opens when a recognized license plate approaches, leveraging OpenCV on a Raspberry Pi for OCR and an Arduino-controlled actuator for the gate.
**This project was completed as part of the Software for Embedded Systems.**


## Features

- Real-time license-plate detection and recognition  
- Gate actuator control via Arduino over serial  
- Configurable whitelist of allowed plates  
- Logging of entry events with timestamp and image capture  

## Hardware 

- Raspberry Pi 4B with 8GB
- Arduino Uno (or similar) 
- USB cable (Pi ↔ Arduino)  
- Gate actuator (e.g. linear actuator or servo)  
- Webcam or Pi Camera module  
- Power supply for Pi, Arduino, and actuator

## Setup

**Clone the repo**

More details inside the documentation

## Usage

- Configure your whitelist in config/whitelist.txt (one plate per line).
- Run the recognition script on the Pi
- When a plate matches, the gate will open automatically and log the event to logs/

## Contributing

Feel free to open issues or submit pull requests. For major changes, please open an issue first to discuss what you’d like to change.

## License

This project is licensed under the MIT License — see the LICENSE file for details.


