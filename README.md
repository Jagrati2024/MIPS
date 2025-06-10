# 32-bit Single-Cycle MIPS Processor (Verilog)

This project implements a **32-bit single-cycle MIPS processor** in Verilog. The processor supports a subset of MIPS instructions and executes each instruction in a single clock cycle.

## ✅ Supported Instructions

The following MIPS instructions are supported:

- **Arithmetic & Logical**: `add`, `sub`, `and`, `or`, `slt`
- **Memory Access**: `lw`, `sw`
- **Branch & Jump**: `beq`, `jal`, `j`

## 🧪 Testbench

A comprehensive **testbench** is included to simulate and verify the functionality of the processor. It performs the following:

- Executes a set of sample MIPS instructions
- Checks correctness of:
  - Register updates
  - Memory read/write operations
  - Branching and jump instructions

## 📸 Simulation Waveform

**Screenshots of simulation waveforms** are provided to demonstrate correct execution of instructions. These visualizations help:

- Understand how each instruction is processed cycle-by-cycle
- Verify internal signal changes and data flow

## 📂 Files

- `mips.v` – Main Verilog implementation of the processor
- `test.v` – Testbench for simulation and validation
- `README.md` – Project documentation
- `*.png` – Waveform screenshots from simulation
- `report.pdf` – (If included) Detailed explanation or lab report

