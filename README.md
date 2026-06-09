# Laser Light Data Transfer System

## Overview

This project demonstrates wireless data communication using a laser beam.

Instead of RF communication modules, digital data is transmitted by modulating a laser beam and received using a light sensor.

## Features

- Laser-based optical communication
- Binary data transmission
- Raspberry Pi Pico implementation
- Custom framing and synchronization
- line-of-sight communication

## Components

- Raspberry Pi Pico 
- Laser Module
- LDR Sensor
- Breadboard
- Jumper Wires

## Working

1. Data is converted into binary.
2. Laser transmits binary bits using ON/OFF pulses.
3. Receiver detects light changes.
4. Binary data is reconstructed into text.

## Test Result

Successfully transmitted the message:

H

over a distance of approximately 1 meters.

## Future Improvements

- BPW34 Photodiode Receiver
- Error Detection (CRC)
- Build Data Transfering Structure
- Real-Time File Transfer
- Multi-Channel Optical Communication

## Skills Demonstrated

- Embedded Systems
- Raspberry Pi Pico
- Optical Communication
- Serial Communication
- Digital Electronics
- Signal Processing
- Protocol Design
