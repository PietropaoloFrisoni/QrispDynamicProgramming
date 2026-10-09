# Qrisp School

**12-13 October 2026, IQM Munich office**

Two days of hands-on introduction to [Qrisp](https://github.com/eclipse-qrisp/Qrisp), our high-level quantum programming framework, held right before the Munich Quantum Software Forum.

Four sessions take you from the programming model to block-encoding-based algorithms. Each session is a lecture followed by an interactive coding part.

This repository only contains the material for [Session 3: Dynamic Programming](Session_3_Dynamic_Programming/). The material of the whole school is collected on an internal Jira page; the other sessions are listed below for reference.

## Schedule

| Time | Mon, 12 Oct | Tue, 13 Oct |
|---|---|---|
| 9:30-12:00 | 1. Qrisp Basics | [3. Dynamic Programming](Session_3_Dynamic_Programming/) |
| 13:00-15:30 | 2. Operators | 4. Block Encodings |

## Sessions

### 1. Qrisp Basics (Monday morning)

- **Lecture:** The general programming model and how it differs from Qiskit. QuantumVariables and quantum types, quantum environments, memory management.
- **Tutorial:** Small programming exercises that introduce each of these on concrete examples, plus transpilation passes, the PassManager, and pulse-level access.

### 2. Operators (Monday afternoon)

- **Lecture:** The operators module in Qrisp: Pauli strings, ladder operators, fermionic operators, how ladder operators are implemented, Hamiltonian simulation, and expectation values.
- **Tutorial:** Load chemistry data from PySCF and simulate molecules; construct entanglement witnesses and measure them on hardware.

### 3. Dynamic Programming (Tuesday morning)

- **Lecture:** Why we need dynamic programs at all: scalability and real-time computation for QEC. Introduction to JAX and Just-in-time compilation, and how it embeds into Qrisp with the Jasp module (dynamic control flow, dynamic variables, and compilation pipeline).
- **Tutorial:** Write dynamic programs yourself in Qrisp with dynamic mode leveraging JAX. Evaluation modes: resource estimation, boolean simulation, and other Jasp-related features for quantum programming.

### 4. Block Encodings (Tuesday afternoon)

- **Lecture:** The mathematical foundations: what is a block encoding, and why is it useful? Which constructions exist, and which algorithms operate on block encodings.
- **Tutorial:** LCU, qubitization and Chebyshev in code, along the lines of the examples on the Qrisp website.

## Resources

- Qrisp documentation: https://www.qrisp.eu/
- Qrisp on GitHub: https://github.com/eclipse-qrisp/Qrisp
