# Python CPU Simulator

A small CPU simulation written in **Python** to explore how processors coordinate registers, instructions, memory, and cache behavior.

## Features

- Nine simulated CPU registers
- Program/instruction counter
- File-based instruction input
- File-based memory initialization
- Simulated memory bus
- Cache layer with enable, disable, and flush operations
- Instruction parsing and execution

## Supported Instructions

| Instruction | Purpose |
| --- | --- |
| `ADD` | Add values from two registers and store the result |
| `ADDI` | Add an immediate value to a register value |
| `J` | Change the instruction/program counter |
| `CACHE` | Toggle or flush the simulated cache |

## Project Structure

The simulator separates processor, memory, and cache responsibilities into individual Python modules. `main.py` initializes memory from input files and sends instructions to the CPU for parsing and execution.

## Running the Simulator

```bash
python main.py
```

The simulator reads its initial data and instruction stream from:

```text
data_input.txt
instruction_input.txt
```

## What This Project Demonstrates

This project demonstrates object-oriented Python, state management, file I/O, instruction parsing, and foundational computer-architecture concepts such as registers, memory access, caches, and processor control flow.

## Author

**Matthew Tedesco**
