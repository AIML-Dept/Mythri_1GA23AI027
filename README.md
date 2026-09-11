# Quantum Computing Tutorials

## Course Information

- **Course Name:** Quantum Computing
- **Course Code:** AML23703
- **Department:** Artificial Intelligence and Machine Learning
- **Faculty:** Dr. Roopa B. S
- **Institution:** Global Academy of Technology
- **Student Name:** Mythri M R
- **USN:** 1GA23AI027

---

# Tutorial 1: Introduction to Quantum Computing and Qiskit Environment Setup

## Objective

The objective of this tutorial is to understand the fundamentals of quantum computing using Qiskit. The tutorial demonstrates quantum superposition, quantum measurement, and quantum random number generation through practical implementation.

---

## Software Used

- Python
- Jupyter Notebook
- Qiskit
- Qiskit Aer
- NumPy
- Matplotlib

---

## Exercises Completed

- ✅ Verified Qiskit installation
- ✅ One-Qubit Hadamard Circuit
- ✅ Three-Qubit Superposition
- ✅ Quantum Random Number Generator

---

## Results

- Successfully created and simulated quantum circuits.
- Generated measurement histograms.
- Demonstrated quantum superposition.
- Compared classical and quantum random number generation.

---

# Tutorial 2: Qubits, State Vectors and Superposition Visualization

## Objective

The objective of this tutorial is to understand qubit representation using state vectors and Dirac notation. The tutorial demonstrates quantum superposition, probability amplitudes, and quantum state visualization through practical implementation using Qiskit.

---

## Software Used

- Python
- Jupyter Notebook
- Qiskit
- NumPy
- Matplotlib

---

## Exercises Completed

- ✅ Single-Qubit State using Pauli-X Gate
- ✅ Hadamard and Phase (S) Gates
- ✅ Two-Qubit Equal Superposition
- ✅ Probability Verification
- ✅ Real-World Quantum Communication Example
- ✅ Arbitrary Qubit State Generation

---

## Results

- Successfully created and simulated single and two-qubit circuits.
- Generated and analyzed quantum state vectors.
- Verified quantum probability normalization.
- Demonstrated superposition using Hadamard gates.
- Explored Bloch Sphere and Q-Sphere concepts.
- Applied quantum gates to generate different quantum states.

---

# Tutorial 3: Single-Qubit Quantum Gates

## Objective

The objective of this tutorial is to understand the operation of fundamental single-qubit quantum gates using Qiskit. The tutorial demonstrates quantum state transformations, gate combinations, and simple quantum applications through practical implementation and visualization.

---

## Software Used

- Python
- Jupyter Notebook
- Qiskit
- NumPy
- Matplotlib

---

## Exercises Completed

- ✅ Pauli-X, Pauli-Y, and Pauli-Z Gates
- ✅ Construction of the |−⟩ State
- ✅ Five Single-Qubit Gate Sequence
- ✅ Quantum Coin Flip Simulation

---

## Results

- Successfully implemented and analyzed single-qubit quantum gates.
- Constructed the |−⟩ state using Hadamard and Pauli-Z gates.
- Verified quantum state transformations using state vectors.
- Visualized quantum states using Bloch Sphere, Q-Sphere, and State City plots.
- Simulated a quantum coin flip and analyzed measurement probabilities.

---

# Tutorial 4: Multi-Qubit Gates and Circuit Composition

## Objective

The objective of this tutorial is to understand and implement multi-qubit quantum gates using Qiskit. The tutorial demonstrates controlled operations, quantum entanglement, multi-qubit state preparation, and circuit composition through practical implementation and visualization.

---

## Software Used

- Python
- Jupyter Notebook
- Qiskit
- Qiskit Aer
- NumPy
- Matplotlib

---

## Exercises Completed

- ✅ CNOT Gate
- ✅ Bell State
- ✅ Three-Qubit GHZ State
- ✅ Quantum Full Adder
- ✅ Custom Two-Qubit Entangled State

---

## Results

- Successfully implemented CNOT, CZ and Toffoli-based multi-qubit operations.
- Verified target-qubit flipping using the CNOT gate.
- Created and analyzed Bell and GHZ entangled states.
- Verified entanglement using state vectors and measurement results.
- Implemented a quantum full adder using CNOT and Toffoli gates.
- Created a custom two-qubit entangled state with unequal probabilities.
- Visualized quantum circuits, probability distributions, and measurement outcomes.

---

# Tutorial 5: Quantum Measurement and Probability Analysis

## Objective

The objective of this tutorial is to understand quantum measurement, probability distributions, measurement bases, state collapse, and statistical convergence using Qiskit. The tutorial also explores quantum state estimation and quantum randomness through practical implementation and visualization.

---

## Software Used

- Python
- Jupyter Notebook
- Qiskit
- Qiskit Aer
- NumPy
- Matplotlib
- SciPy

---

## Exercises Completed

- ✅ Hadamard Measurement and Probability Convergence
- ✅ X-Basis Measurement
- ✅ Partial Measurement of a Bell Pair
- ✅ Quantum State Tomography
- ✅ Quantum Randomness vs Classical Pseudo-Randomness

---

## Results

- Successfully analyzed quantum measurement probabilities using different numbers of shots.
- Demonstrated convergence of measured probabilities toward theoretical values.
- Performed X-basis measurement using Hadamard transformations.
- Demonstrated state collapse and correlation through partial measurement of an entangled Bell pair.
- Estimated quantum state rotation angles using measurement statistics.
- Compared quantum randomness with biased classical pseudo-randomness.
- Applied chi-square statistical testing to analyze randomness.
- Visualized probability distributions, measurement results, and state estimation using graphs and histograms.

---
# Tutorial 6: Simon's Algorithm — Concept and Implementation

## Objective

The objective of this tutorial is to understand and implement Simon's algorithm, construct and verify Simon's oracle, obtain measurement equations, solve the resulting system of linear equations over GF(2), compare quantum and classical oracle-query requirements, and implement a generalized Simon's algorithm for arbitrary secret bitstrings.

---

## Software Used

- Python
- Jupyter Notebook
- Qiskit
- Qiskit Aer
- NumPy
- Pandas
- Matplotlib

---

## Exercises Completed

- ✅ Simon's Oracle for Secret String 110
- ✅ Complete Simon's Algorithm for a 3-Bit Secret String
- ✅ 4-Bit Simon's Algorithm and GF(2) Linear Equation Solving
- ✅ Quantum vs Classical Oracle Query Comparison
- ✅ Generalized Simon's Algorithm with All-Zero Edge Case

---

## Results

- Successfully constructed and verified Simon's oracle for the secret string 110 using a complete truth table.
- Verified the Simon condition f(x) = f(x ⊕ s) for all possible input combinations.
- Obtained measurement bitstrings satisfying y · s = 0 mod 2.
- Collected independent equations required to determine the hidden secret string.
- Extended Simon's algorithm to a 4-bit secret string and solved the resulting equations over GF(2).
- Compared quantum and classical oracle-query requirements and visualized the increasing speedup.
- Implemented a generalized Simon's algorithm that accepts arbitrary secret bitstrings.
- Successfully handled the all-zero secret-string edge case.
- Visualized oracle circuits, measurement histograms, query complexity, and speedup using graphs.

---
# Tutorial 7: Deutsch's Algorithm — Demonstrating Quantum Advantage

## Objective

The objective of this tutorial is to understand Deutsch's algorithm and demonstrate how a quantum computer can determine whether a Boolean function is constant or balanced using a single quantum query.

---

## Software Used

- Python
- Jupyter Notebook
- Qiskit
- Qiskit Aer
- NumPy
- Matplotlib

---

## Exercises Completed

- ✅ Constant Function f(x) = 0
- ✅ Balanced Function f(x) = x
- ✅ Generic Oracle Selection for All Four Boolean Functions
- ✅ Phase Kickback and Binary Classification Application
- ✅ Imperfect Hadamard Gate and Measurement Reliability

---

## Results

- Successfully implemented Deutsch's algorithm for the constant function f(x) = 0 and obtained measurement result 0.
- Implemented the balanced function f(x) = x and obtained measurement result 1.
- Constructed a generic oracle-selection function for all four possible single-bit Boolean functions.
- Verified that constant functions produce 0 while balanced functions produce 1.
- Demonstrated the conceptual application of phase kickback to binary classification using a visual diagram.
- Introduced a deliberate small Hadamard gate error and observed its effect on measurement reliability.
- Visualized the effect of the gate error using a bar chart.
- Demonstrated the quantum advantage of determining whether a Boolean function is constant or balanced using a single quantum query.
---

## Author

**Mythri M R**

Department of Artificial Intelligence and Machine Learning

Global Academy of Technology
