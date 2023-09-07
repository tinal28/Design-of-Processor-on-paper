# Custom Processor Design Project

Welcome to the Custom Processor Design Project repository. This project focuses on the development of a tailored processor specifically designed for high-speed operations in an Industry 4.0 compliant factory setting. The primary objective is to meet throughput demands that cannot be adequately addressed by readily available off-the-shelf embedded processors.

## Project Overview

The objective of this project is to create a customized processor as an integral component of a System on Chip (SoC) for use in a high-speed factory environment. This processor is designed to function independently, without relying on an operating system, and will be programmable through assembly language code generated from C language programs. To attain the targeted throughput, we are implementing pipeline processing techniques.

## Processor Specifications

The processor specifications provided for this project include details about memory, registers, ALU, addressing modes, instruction set, and more. The following aspects are covered:

- Data Memory and Program Memory specifications
- Register file details including the Stack Pointer
- ALU and addressing modes
- Instruction set supporting arithmetic, control flow, load/store, and data transfer operations
- Instruction formats and their justifications
- Encoding scheme for opcodes
- Microarchitecture design approach: Hardwired or Microprogrammed
- Datapath design with functional elements and control signals
- Controller design for the chosen datapath

## Project Components

- **Instructions and Formats**: A detailed list of required instructions, their formats, opcodes, operands, and their meanings.
- **Encoding Scheme**: Proposals for an opcode encoding scheme that ensures easy and efficient decoding of instructions.
- **Datapath Design**: A clear diagram depicting the datapath with functional components and control signals.
- **Microarchitecture Approach**: Explanation of the chosen microarchitecture approach (Hardwired or Microprogrammed) with justifications.
- **Controller Design**: Detailed design of the controller for the datapath, illustrating inputs, outputs, and reasons for design decisions.
