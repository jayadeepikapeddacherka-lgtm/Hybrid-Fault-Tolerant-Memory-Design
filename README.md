# Hybrid-Fault-Tolerant-Memory-Design
Hybrid Fault-Tolerant 64x16 RAM using ECC and BIST in SystemVerilog

## Overview

This project implements a Hybrid Fault-Tolerant Memory System using a 64×16 RAM integrated with Error Correction Code (ECC) and Built-In Self-Test (BIST) techniques.

The design improves memory reliability by detecting, correcting, and isolating faults automatically.

## Features

- 64×16 RAM Architecture
- Hamming SEC-DED ECC
- Single Error Correction
- Double Error Detection
- Built-In Self-Test (BIST)
- Fault Detection and Isolation
- SystemVerilog Implementation
- QuestaSim Verification

## Modules

### RAM Module
- 64 memory locations
- 16-bit data width
- Read and write operations

### ECC Encoder
- Generates 21-bit encoded data
- Adds parity bits

### ECC Decoder
- Detects memory errors
- Corrects single-bit faults

### BIST Controller
- Automatic memory testing
- Detects permanent faults

### Top Module
- Integrates RAM, ECC and BIST

## Tools Used

- SystemVerilog
- QuestaSim
- Digital VLSI Design

## Results

- Successful simulation
- Fault detection achieved
- Single-bit error correction verified
- 100% coverage achieved

## Future Enhancements

- Multi-bit error correction
- Larger memory architectures
- Processor integration
- Low-power optimization

