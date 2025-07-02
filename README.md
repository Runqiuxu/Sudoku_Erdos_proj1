# Quantum Sudoku Solver (2x2) with Grover's Algorithm

This project implements a **quantum Sudoku solver** for a simplified 2x2 Sudoku grid using **Grover's algorithm** with Qiskit. It leverages quantum superposition and oracle design to mark valid Sudoku solutions and amplify their amplitudes, demonstrating how quantum search algorithms can tackle combinatorial constraint problems.

## Project Structure

* `sudoku_grover.py` — Main circuit construction and oracle logic.
* `run_sudoku.py` — Example usage and simulation.

## Usage

Run the Python script or import the functions to:

```python
from sudoku_grover import build_grover_sudoku_2x2
from qiskit.quantum_info import Statevector

qc = build_grover_sudoku_2x2(iterations=1)
state = Statevector.from_instruction(qc)
probs = state.probabilities()
print(probs)
```

Adjust `iterations` to tune Grover amplification steps.
