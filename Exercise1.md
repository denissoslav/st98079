# Exercise 1: Understanding the vnmsim Interface

## 1. Objective

The objective of this exercise is to become familiar with the vnmsim simulator interface and identify components related to the Von Neumann architecture.

## 2. Overview of the Interface

The vnmsim interface displays a simplified computer system with processor registers, an arithmetic logic unit, memory, and connections between components. The main workspace contains the processor diagram, register controls, and execution controls.

## 3. Components Identified

### ALU (Arithmetic Logic Unit)

The ALU performs arithmetic and logical operations on values supplied to it. It is an essential component of the processor.

### ACC (Accumulator)

The accumulator stores intermediate results produced during calculations and processing operations.

### IR (Instruction Register)

The instruction register holds the instruction currently being processed by the processor.

### Decoder

The decoder interprets the instruction stored in the instruction register and determines which operation should be performed.

### PC (Program Counter)

The program counter stores the address associated with the next instruction to be fetched or executed, depending on the current execution stage.

### RAM (Random Access Memory)

RAM represents the main memory of the computer. It stores program instructions and data required during execution.

### Data Bus

The data bus provides a communication pathway for transferring data between components such as the processor and memory.

### Address Bus (Add. bus)

The address bus carries memory addresses used to identify the locations from which data or instructions are accessed.

### Additional Registers

The interface also displays registers named X, Y, Z, W, and T0. These registers provide storage for values used by the simulated processor.

## 4. Relationship to the Von Neumann Architecture

The Von Neumann architecture is based on a processor, memory, input/output mechanisms, and communication pathways connecting these components. One of its key principles is that program instructions and data are stored in the same memory system.

The RAM shown in vnmsim represents the memory component. The Program Counter identifies instruction addresses, while the Instruction Register holds the current instruction. The Decoder interprets instructions, and the ALU performs arithmetic and logical operations. The Accumulator stores intermediate calculation results.

The data bus and address bus represent communication pathways that allow the processor and memory to exchange information.

A separate input/output device is not clearly visible in the screenshot. Therefore, this report focuses on the components that can be identified directly in the simulator interface.

## 5. Conclusion

This exercise provided an introduction to the vnmsim simulator interface and its main components. The ALU, accumulator, instruction register, decoder, program counter, RAM, and buses demonstrate important concepts of processor organization and the Von Neumann architecture.

Exploring these components helps explain how instructions are handled, how data is processed, and how information moves between the processor and memory.

## 6. Screenshot

The screenshot of the vnmsim interface is included in this repository as `vnmsim-interface.png`.
