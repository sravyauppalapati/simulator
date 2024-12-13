# simulator

Overview

The Assembler and Simulator project is designed to bridge the gap between assembly language and binary machine code, and to simulate the execution of these machine instructions.

This project comprises two main components:

Assembler: Converts human-readable assembly language instructions into binary code understandable by machines.
Simulator: Executes the generated binary instructions to simulate the behavior of a CPU.
It is a crucial tool for understanding low-level programming and machine operations, providing hands-on learning for computer architecture enthusiasts.

Features

🖋 Assembler
Translation:
Converts assembly instructions (opcodes, operands, labels) into corresponding binary instructions.
Error Detection:
Identifies syntax errors, invalid opcodes, missing labels, or incorrect operands.
Symbol Table Generation:
Maps labels to memory addresses for easy reference during translation.
Human-Readable Output:
Provides verbose logs for debugging, showing assembly code alongside its binary translation.
🖥 Simulator
Binary Code Execution:
Simulates the execution of binary machine instructions.
Instruction Set Support:
Executes common operations like arithmetic, logical, load/store, and control flow.
Memory Management:
Simulates memory allocation for code and data.
Runtime Debugging:
Displays registers, memory state, and current instruction during execution.
