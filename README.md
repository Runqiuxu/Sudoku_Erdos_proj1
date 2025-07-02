# Quantum Sudoku Solver (2x2) with Grover's Algorithm

This project implements a **quantum Sudoku solver** for a simplified 2x2 Sudoku grid using **Grover's algorithm** with Qiskit. It leverages quantum superposition and oracle design to mark valid Sudoku solutions and amplify their amplitudes, demonstrating how quantum search algorithms can tackle combinatorial constraint problems.

## Project Structure

* `sudoku_grover.py` — Main circuit construction and oracle logic.
* `run_sudoku.py` — Example usage and simulation.
* Adjust `iterations` to tune Grover amplification steps.
