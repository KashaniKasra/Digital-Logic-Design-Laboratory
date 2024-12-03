## Project Overview

This project focuses on **Sequential Synthesis and FPGA Programming**. The main objective is to design and implement a **Multi-channel Serial Transmitter** (MSSD) using Finite State Machines (FSMs) and related components on an FPGA. The design includes concepts such as state machines, sequence detectors, and synthesis.

## Contents

- `Instruction.pdf`: Detailed instructions for the experiment.
- `Report.doc`: Documentation covering design, implementation, and results.

## Key Components

### 1. Multi-channel Serial Transmitter (MSSD)
The MSSD is a synchronous communication demultiplexer. It receives serial input, decodes the data, and routes it to specific output ports.
   - Transmission is initiated when a bit transition (1 to 0) is detected. The serial data stream includes the destination port, data size, and the data itself.

### 2. RTL Design
   - **Onepulser**: Generates a clock enable signal used for controlling the system clock in the FPGA.
   - **Finite State Machine (FSM)**: Implements the control logic for handling the serial data stream and routing it to the appropriate output port.
   - **Shift Registers & Demultiplexer**: Shift registers are used for storing port numbers and data bits, and the demultiplexer selects the appropriate output channel.
   - **Seven-Segment Display**: Displays the number of data bits transmitted to the selected port.

### 3. FPGA Implementation
The design is synthesized and implemented on an FPGA development board (Cyclone II). Inputs such as the serial data and clock are provided through the board’s switches and push-buttons. LEDs and a seven-segment display are used to show data transmission status and results.

## Deliverables
- Simulation results for various components like the one-pulser, FSM, and shift registers.
- Verilog code for each module.
- Synthesis report and FPGA resource utilization.
- Demonstration of the MSSD design implemented on the FPGA.

This project is part of a laboratory course at the University of Tehran, supervised by Professor Zain Navabi.