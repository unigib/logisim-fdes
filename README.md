# CSS4105 Logisim Circuits and CPU Assignments

This repository contains a collection of Logisim digital logic circuits created for CSS4105 coursework and related computer architecture study. The files are designed to help students explore how a processor works at the hardware level, from simple logic gates and registers to complete CPU-style datapaths and memory systems.

The work focuses on CPU-related circuits and the fetch-decode-execute model that forms the core of most processor architectures. Each circuit is an educational schematic intended to make abstract concepts visible and easier to understand.

## Purpose

These circuits are used to teach and demonstrate:

- digital logic design
- clocking and synchronous behaviour
- memory read/write operations
- program counter and register activity
- instruction fetch and decode logic
- arithmetic and control logic
- basic CPU datapaths and execution flow

This repository is especially useful for students studying computer organisation, digital systems, or architecture fundamentals.

## Main topics covered

- Basic logic and combinational design
- Memory and storage circuits
- Clock and timing behaviour
- Seven-segment display and output logic
- CPU fetch-decode-execute flow
- Register transfer and control signals
- Simple processor architecture and datapath design

## Repository files

### CPU and processor circuits

- `cpu_fetch_decode_execute.circ` – a central fetch-decode-execute circuit showing the main stages of instruction processing.
- `fix-cpu_fetch_decode_execute.circ` – a revised or corrected version of the fetch-decode-execute design.
- `simple_cpu_v1a.circ` – a simple educational CPU implementation.
- `dhr-simple_cpu_v1a.circ` – another variation of the simple CPU design.
- `simple_cpu_v1a.orig.circ` – original version for comparison.
- `simple_cpu_v1a.orig - mig.circ` – alternate historical copy.

### Memory and supporting hardware

- `memory_basic.circ` – introductory memory circuit illustrating read/write behaviour and addressing.
- `clock_assignment.circ` – clocking and timing circuit used to explore synchronous circuit behaviour.
- `seven_segment_component.circ` – seven-segment display circuit for output visualisation.
- `sopdhr.circ` – logic design-oriented circuit related to Boolean simplification and control logic.

### Data and notes

- `data.txt` – sample data used with memory or CPU circuits.
- `truthtable.txt` – logic truth table reference.
- `sevenseg.txt` – data related to seven-segment output.
- `logisim_memory_schematic.txt` – notes or schematic description for memory design.

### Web teaching materials

- `simple_cpu_logisim/` – a small set of HTML pages and images used to present the CPU design and related digital logic concepts visually.

## How to use this repository

1. Open the `.circ` files in Logisim or Logisim Evolution.
2. Simulate the circuits to observe signal flow and state changes.
3. Study how clocks, registers, memory, and control signals interact.
4. Use the CPU examples to understand how instructions are processed step by step.

## Educational context

These files are intended as teaching resources for CSS4105-style assignments and learning activities. They are not intended to represent a production CPU, but rather a clear, visual way to understand the core building blocks of computer hardware.

This project is best viewed as a practical introduction to how a processor is built from logic, memory, control, and timing components.

## Notes

The circuits in this repository are useful for:

- classroom demonstrations
- lab assignments
- digital logic exercises
- studying fetch-decode-execute behaviour
- understanding CPU hardware at a schematic level

The goal is to help learners connect theory to visible circuit behaviour, especially in the context of computer architecture and embedded digital systems.
