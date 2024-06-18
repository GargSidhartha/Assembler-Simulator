# CO-Project: Assembler and Simulator 🖥️🔧

## Overview
This project, developed by Somay Jalan (2022505), Swarnima Prasad (2022525), Tanishk Singh (2022612), and Sidhartha Garg (2022499), comprises an assembler and simulator with specific features tailored for the course.

## Folder Structure 📂
- `/CO_A_P1/Simple_Assembler`: Contains `assembler_final.py` with `stdin` and `stdout` functionality for the assembler.
- `/CO_A_P1/final_assembler`: Contains `assembler_final.py` with input from `input.txt` and output to `output.txt`.
- `/final_simulator`: Contains the simulator which takes binary input (`stdin`) and outputs the trace (`stdout`).
- `/Q3`: Includes folders with assembler and simulator code for a specific assignment.

## Usage 🚀
### Assembler
- To use the assembler with `stdin` and `stdout`:
  ```bash
  python /CO_A_P1/Simple_Assembler/assembler_final.py
  ```
- For file-based input/output:
  ```bash
  python /CO_A_P1/final_assembler/assembler_final.py < input.txt > output.txt
  ```

### Simulator
- To run the simulator:
  ```bash
  python /final_simulator/simulator.py
  ```
- The simulator reads binary input (`stdin`) and outputs the execution trace (`stdout`).

### Automated Testing 🧪
- Automated tests are available for both the assembler and simulator functionalities to ensure correctness and reliability.

## Features ✨
- **Assembler**: Converts assembly code into machine code for the specified ISA, handling instructions, labels, and variables.
- **Simulator**: Executes machine code, performing operations, computations, and memory dumps.
- **Automated Testing**: Includes a suite of tests to verify functionality and performance.
- **Floating Point Computation**: Supports floating-point operations as part of its instruction set.
- **Error Handling & Flag Register**: Detects and reports errors for invalid instructions, while flag registers handle overflows and other conditions.

## Course Details 📚
- **Instructor**: Tammam Tillo (tammam@iiitd.ac.in)
- **Course Code**: CSE112
