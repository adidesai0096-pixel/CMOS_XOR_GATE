# CMOS XOR Gate Design and Simulation Using LTspice

## Project Overview
This project focuses on the design and simulation of a CMOS XOR gate using four NAND gates at the transistor level.

## Objectives
- Design a CMOS XOR gate using NAND logic.
- Understand CMOS PMOS and NMOS transistor operation.
- Implement transistor-level circuit connections.
- Simulate and analyse the XOR output using LTspice.

## Logic Implementation

The XOR gate is implemented using four NAND gates:

- NAND1 = NAND(A, B)
- NAND2 = NAND(A, NAND1)
- NAND3 = NAND(B, NAND1)
- Output Y = NAND(NAND2, NAND3)

## Truth Table

| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

## Software Used
- LTspice

## Project Files
- CMOS_XOR_PROJECT.asc – LTspice circuit schematic
- XOR_Simulation_Waveform.png – Simulation waveform
- XOR_Circuit_Schematic.png – Circuit screenshot
- Project_Report.pdf – Project documentation

## Learning Outcomes
- CMOS transistor-level circuit design
- NAND gate implementation
- Digital logic simulation
- Waveform analysis using LTspice

## Author
Aditya Ramakant Desai

Electronics and Computer Engineering
