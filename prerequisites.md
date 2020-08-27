# Prerequisites by topic
Breaks down the conceptual and computational requirements of each section by topic. Topics are arranged chronologically based on teaching order, and later topics which require prequisites covered in a previous lecture are highlighted as **PreviousTopic**

### Review
- Covers the following concepts
1. Probability and Statistics
2. Linear Algebra
3. Quantum mechanics postulates
4. Tensor algebra
5. Introduction to physical qubit systems e.g. spin, superconducting qubits

### Quantum Entanglement (QE)

- Quantum Computing Concepts
1. Single-qubit gate (H)
2. Two-qubit gate (CNOT)

- Physics Concepts
1. Quantum mechanics (Superposition)
2. Multi-particle states
3. Physical measurement

### Quantum Teleportation
- Physics Concepts (**QE**)
1. Pauli-spin matrices


### Violation of Bell's Inequalities
- Computational requirements
1. Remote access of QuTools
- Physics Concepts (**QE**)
1. Understanding of a heralded single-photon system
2. Photon polarization as qubit states
3. Basic optics (Waveplates etc.)
4. Bell's inequalities

### Quantum Fourier Transform
- Computational requirements
1. Built-in qiskit function for QFT
- Physics Concepts (**QE**)
1. Classical Fourier Transform

References:
https://qiskit.org/textbook/ch-algorithms/quantum-fourier-transform.html

### Quantum Phase Estmation (QPE)
- Computational requirements
- Physics Concepts (**QE,QFT**)
1. Classical Fourier Transform

References:
https://qiskit.org/textbook/ch-algorithms/quantum-phase-estimation.html

### Variational Quantum Eigensolver Introduction (VQE)
- Additional computational requirements
1. Classical simulation (for comparison)
2. Convex Optimization
-Physics Concepts 
1. Ising model
2. Understanding of molecular hamiltonians

References:
https://arxiv.org/pdf/1302.5843.pdf
https://qiskit.org/textbook/ch-applications/vqe-molecules.html
https://www.nature.com/articles/s41534-020-0259-3

### Quantum Simulation of Schrodinger Equation Introduction (QSSE)
### QSSE for Quantum Tunnelling
- Additional computational requirements
- Physics Concepts (**QFT**)
1. Time evolution of a single-particle system
3. QFT implementation

### QSSE for Quantum Harmonic Oscillator (QHO)
- Additional computational requirements
- Physics Concepts (**QSSE**)
1. Physics of a QHO
