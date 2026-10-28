# Talstelsels

A small web app for working with number systems: binary, octal, decimal and hexadecimal. The interface is in Dutch.

It is a single `index.html` file with no dependencies. Open it in a browser and it works.

## Features

- Bit table: toggle bits (2048 to 1) per row and see the decimal value and binary string
- Converter: convert between binary, octal, decimal and hexadecimal, plus a list of 12 specific conversions with copy buttons
- Theory: short explanations of the hexadecimal and octal systems
- Notes: a text area that saves to the browser's localStorage
- Calculator: basic operations, brackets, percentage, powers, square root, sin, cos, tan, log, ln and π, with keyboard input

Input is validated per number system, and errors are shown in Dutch.

## Usage

Download `index.html` and open it in a browser. No build step or server is needed.

## Notes

- Notes are stored in the browser only, so they are not shared between devices.
- The calculator uses radians by default; the Rad/Deg button switches to degrees.
- The calculator uses its own expression parser instead of `eval`.
