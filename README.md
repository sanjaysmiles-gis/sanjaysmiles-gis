# Arduino-Based Inverter: DC to AC Conversion
This project demonstrates how to build a basic inverter using an Arduino, transistors, and a transformer to convert 12V DC into 220V AC. Perfect for beginners looking to understand the basics of inverter circuits!

## Features
- Converts 12V DC to 220V AC.
- Push-pull transistor configuration.
- Supports basic AC applications.

## Components
- Arduino Uno or Nano.
- Transistors (2N3904) – 2 units.
- Transformer (12V primary to 220V secondary).
- 1.5 kΩ resistors – 2 units.
- 100 µF capacitors – 2 units.
- 12V DC power supply.

## How It Works
The Arduino generates PWM signals on pins D9 and D10, which drive two transistors in a push-pull configuration. The transistors alternate switching the current through the transformer’s primary winding, generating an AC waveform at the secondary winding.
