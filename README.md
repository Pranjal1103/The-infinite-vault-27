# The Infinite Vault - Verilog FSM Puzzle

This project implements a multi-phase digital logic puzzle called **The Infinite Vault** using Verilog. It is designed as a Finite State Machine (FSM) that progresses through five interactive challenge phases.

## Project Overview

Each phase represents a unique logic challenge:
1. **Phase 1 - Code Lock**: Serial code input verification.
2. **Phase 2 - Switch Room**: Switch combination logic.
3. **Phase 3 - Maze Navigation**: Direction sequence tracking.
4. **Phase 4 - Pressure Plates**: Plate activation patterns.
5. **Phase 5 - Time Lock**: Final 2-bit lock confirmation.

If all phases are passed, the vault unlocks (`all_done = 1`).


## Technologies Used

- **Verilog HDL**
- **EDA Playground** for simulation
- **EPWave** for waveform viewing

##  Simulation Output

Simulated using EDA Playground. All five phases were successfully completed.
##  Real-World Applications

- Sequential puzzle circuits
- FSM design training
- Digital system state management
- Locking mechanisms in embedded systems

##  How to Run

1. Clone the repo or open files in [EDA Playground](https://edaplayground.com).
2. Load all `.v` files.
3. Run the testbench.
4. Observe waveforms using EPWave viewer.

