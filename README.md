# 4-bit Arithmetic Logic Unit (ALU)

A 4-bit Arithmetic Logic Unit (ALU) designed using Verilog HDL and Cadence Virtuoso, supporting arithmetic, logical, and bit manipulation operations. The project was functionally verified through simulation and successfully implemented on a Xilinx Basys 3 FPGA using Vivado.

---

## Overview

The ALU is one of the fundamental building blocks of a processor. This project demonstrates the complete digital design flow—from RTL development and circuit design to simulation and FPGA implementation.

The design follows a modular architecture where each functional block is developed independently and integrated to form the complete ALU.

---

## Features

- 4-bit modular ALU architecture
- Arithmetic Operations
  - Addition
  - Subtraction
- Logical Operation
  - XNOR
- Bit Manipulation
  - Rotate Left
  - Rotate Right
- 3-bit control signal based operation selection
- Hierarchical Verilog design
- Functional simulation using Vivado/ModelSim
- Hardware implementation on Xilinx Basys 3 FPGA
- Circuit-level implementation using Cadence Virtuoso

---

## Design Flow

1. Designed individual functional modules:
   - Full Adder
   - Full Subtractor
   - Multiplexers
   - Rotation Circuits

2. Integrated all modules into a complete 4-bit ALU.

3. Developed RTL in Verilog HDL.

4. Verified functionality using simulation waveforms.

5. Synthesized and implemented the design on the Basys 3 FPGA.

---

## Tools Used

- Verilog HDL
- Cadence Virtuoso
- Xilinx Vivado
- ModelSim
- Basys 3 FPGA

---


## Learning Outcomes

Through this project I gained practical experience in:

- RTL design using Verilog HDL
- Hierarchical and modular digital design
- Functional verification using simulation
- FPGA synthesis and implementation
- Circuit design using Cadence Virtuoso
- Digital datapath design and operation selection using multiplexers

---

## Future Improvements

- Parameterized N-bit ALU
- Additional logical operations (AND, OR, XOR, NAND, NOR)
- Status flags (Carry, Zero, Overflow, Negative)
- Barrel shifter implementation
- Self-checking testbench with automated verification
- Timing and resource utilization analysis

---

## Author

**Chhavi Verma**

B.Tech, Electronics and Communication Engineering

Rajiv Gandhi Institute of Petroleum Technology (RGIPT)
