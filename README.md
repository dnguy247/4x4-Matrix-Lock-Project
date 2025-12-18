# 4×4 Matrix Keypad Door Lock
A hardware-only passcode security system built using discrete combinational and sequential logic.

## Project Demo
[![Watch the Demo](https://img.youtube.com/vi/0v9D-uy3l6E/0.jpg)](https://www.youtube.com/watch?v=0v9D-uy3l6E)

## Project Overview
This project implements a 4-digit keypad lock system without the use of microcontrollers. The design relies entirely on digital logic ICs to handle keypad scanning, sequence verification, and output activation.

### Key Technical Features
- **Row-Scanning Logic:** Utilizes a CD4017 decade counter to drive active rows, significantly simplifying wiring and logic requirements.
- **Passcode Verification:** Uses a 4-bit verification circuit with flip-flops to ensure digits are entered in the correct sequence.
- **Resource Efficiency:** Achieved a **25% reduction in total gate count** compared to the initial prototype by optimizing the logic architecture.
- **Stability:** Integrated debounce filtering and pull-down resistors to ensure reliable operation and prevent false key detections.

## Technical Specifications
- **Logic Type:** Discrete Sequential & Combinational Logic
- **Primary ICs:** CD4017 (Decade Counter), 74-series Logic Gates (AND, OR, NOT)
- **Power Management:** LM7805 voltage regulator (12V to steady 5V DC)
- **Input:** 4x4 Matrix Keypad
- **Output:** Relay activation (supports solenoid or LED indicators)

## Repository Contents
- **Schematics:** Full hand-drawn and digital logic diagrams.
- **Report:** Detailed technical analysis, including trade-off studies between scanning methods.
- **Images:** High-resolution photos of the physical breadboard implementation.

--- 
Independent Project by Dylan Nguyen | Electrical Engineering student at UC Santa Cruz
