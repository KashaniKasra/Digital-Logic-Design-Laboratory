## Project Overview

This project focuses on the design and implementation of **Accelerator and Wrappers** in a System on Chip (SoC) environment. The project aims to demonstrate how hardware accelerators can be used to perform specific computations efficiently and integrated into a larger system.

## Contents

- `Instruction.pdf`: Detailed instructions for the experiment.
- `Report.doc`: Documentation covering design, implementation, and results.

## Key Components

### 1. Exponential Engine
The accelerator designed to compute exponential values. It processes a 16-bit input and outputs a fractional and integer part.
   - Tasks include running ModelSim simulations, synthesizing the design in Quartus II, and analyzing the maximum frequency using the Timing Analyzer.

### 2. Exponential Accelerator Wrapper
A wrapper around the exponential engine to handle multiple exponential calculations efficiently.
   - The project demonstrates how to calculate multiple values in parallel to reduce timing overhead caused by handshaking signals between the CPU and accelerator.
   - This section focuses on integrating the exponential engine with shift registers, a FIFO buffer, and a controller for proper signal management.

### 3. Implementing the Accelerator on FPGA
Synthesize the design and implement it on an FPGA, using LEDs and switches to control the operation and display the results.

## Deliverables
- Simulated results for different input values.
- FPGA synthesis reports for both the Exponential Engine and Accelerator Wrapper.
- Detailed analysis of the frequency and performance metrics.

This project is developed as part of a laboratory course at the University of Tehran, under the supervision of Professor Zain Navabi.