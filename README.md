# The Purpose

The purpose of this project is to build an 8-bit central processing unit (CPU) from scratch in *Logic-Sim Evolution*, which can be found in the following GitHub repository: [https://github.com/logisim-evolution/logisim-evolution](https://github.com/logisim-evolution/logisim-evolution). In my opinion, the best way to understand (and master) a skill is through practice and doing it. :)

# Timing

In this design, the data bus is 8 bits wide, and the instructions are 16 bits long. Generally, two steps are designed for the functioning, and each step consists of 2 periods of the base clock. The first step is when the device detects the opcode; in this stage, the control unit's instruction register is written. The second step is the execution, during which the central unit's instruction register is read.

# The Parts of the CPU

The design has 4 fundamental elements: the memory (RAM for the data, ROM for the program, and the registers), the Arithmetic Logic Unit (ALU), the environment of the data transfer (program counter and data bus), and the control unit.
