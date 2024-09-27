Project Name - Morse Code LED Blinking Project
Overview
This project demonstrates the use of a microcontroller to output Morse code for the letters 'A' (".-") and 'S' ("...") using an LED. The LED blinks in a pattern corresponding to Morse code signals: short blinks for dots (.) and long blinks for dashes (-).

Objective

To simulate Morse code for letters 'A' and 'S' using basic embedded C programming and GPIO control for an LED.
Hardware Used

Microcontroller: STM32 L432 KC.
LED: A single LED connected to a GPIO pin.
Resistor: 220Ω resistor to limit current to the LED.
Breadboard and jumper wires.
Morse Code Patterns

A: ".-" (dot-dash), which translates to:
Short blink (dot .)
Long blink (dash -)
S: "..." (dot-dot-dot), which translates to:
Three short blinks (dots ...)
How it Works

The LED is connected to a GPIO pin of the microcontroller.
The microcontroller sends a series of HIGH and LOW signals to the pin, creating a pattern of short and long blinks to represent the Morse code for A and S.
Time intervals are used to distinguish between dots, dashes, and letter spacing.
