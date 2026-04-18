<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project takes a 4-bit binary input via DIP switches and displays a corresponding character on a 7-segment display. The input bits are processed through a combinational logic gate network (AND, NAND, NOR gates) that decodes the binary value and drives the correct segments. For example, inputting **1010** displays the letter **U** on the display. A red LED serves as a power/activity indicator.

## How to test

1. Connect VCC and power up the circuit.
2. Set the DIP switches to a 4-bit binary value (e.g. **1010**).
3. The 7-segment display will show the corresponding decoded character.
4. Try different switch combinations to see the other mapped outputs.

## External hardware

- 4-position DIP switch array
- Single-digit 7-segment LED display
- Red indicator LED
