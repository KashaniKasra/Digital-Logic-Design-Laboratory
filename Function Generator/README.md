## Project Overview

This project involves a **Function Generator** that provides users with the ability to generate various waveforms such as sine, square, and triangular waves for different applications. The project documentation includes both instructions for setup and a detailed report.

## Contents

- `Instruction.pdf`: Provides detailed instructions on how to set up and operate the function generator.
- `Report.doc`: A comprehensive report explaining the theory, design, and testing results of the function generator.

## Project Summary

The **Function Generator** project, developed as part of a laboratory course at the University of Tehran, involves creating a digital function generator that can generate waveforms such as sine, square, triangle, and arbitrary waveforms using FPGA components. The project is divided into several key modules:

1. **Waveform Generator**:
   - Generates waveforms using Direct Digital Synthesis (DDS) and a ROM-based approach.
   - Supports sine, square, triangle, reciprocal, and rectified waveforms.

2. **Digital to Analog Conversion (DAC)**:
   - Utilizes a PWM-based approach to convert digital signals to analog, filtered through an RC low-pass filter.

3. **Frequency Selector**:
   - A counter-based module that allows users to set output signal frequency.

4. **Amplitude Selector**:
   - Adjusts waveform amplitude based on user input via FPGA switches.

The project culminates in a full design synthesis, simulation of results, and verification via an oscilloscope.