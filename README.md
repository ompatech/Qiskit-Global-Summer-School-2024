# Qiskit Global Summer School Labs

## Overview

This repository contains the Jupyter notebooks and related materials from my participation in the **Qiskit Global Summer School 2024**. Throughout this program, I gain a deep understanding of quantum computing concepts and practical experience using Qiskit, an open-source quantum computing software development framework.

## Labs

The labs in this repository cover a range of topics in quantum computing, including:

1. **Lab 1: Quantum Circuit Transpilation**:
   - This lab demonstrates Qiskit's transpilation capabilities, which generate hardware-compliant quantum circuits for a given quantum algorithm.
   - It covers key aspects of transpilation, such as synthesis and routing, and shows how to create custom transpilation passes. The lab highlights how Qiskit's adaptable transpilation process optimizes quantum circuits for different quantum computers, enhancing their accuracy and efficiency.
   - The lab focuses on the quantum Fourier transform (QFT) circuit, showcasing its transpilation to an IBM Quantum computer.

2. **Lab 2: Utility-Scale Layer Fidelity Experiment**:
   - This lab demonstrates the calculation of EPLG (Error Per Layered Gate) and LF (Layer Fidelity), which are metrics used to quantify error rates in a quantum circuit. These metrics are particularly useful for understanding the overhead required for error mitigation in utility-scale workloads.
   - It guides through constructing the necessary circuits and using Qiskit Runtime Primitives to perform these calculations. It includes graded exercises and a walkthrough of the Qiskit Runtime implementation for utility-scale calculations.
   - The lab covers setting up the layers and circuits, constructing EPLG circuits, and analyzing the data to extract EPLG and LF metrics.

3. **Lab 3: Quantum Error Suppression and Mitigation with Qiskit Runtime**:
   - This lab demonstrates the use of error suppression and mitigation techniques with the Estimator primitive from Qiskit Runtime.
   - It involves constructing a quantum circuit and observables, submitting jobs using the Estimator primitive with different error mitigation settings, and plotting the results to observe the effects of these settings.
   - The error suppression and mitigation options explored include:
     - Dynamical decoupling
     - Measurement error mitigation
     - Gate twirling
     - Zero noise extrapolation (ZNE)

4. **Lab 4: Simulating Nature at Utility Scale**:
   - This lab explores utility-scale simulations by studying the dynamics of a large Heisenberg spin chain. The objective was to measure the dynamics of a specific site as a function of time and external field strength for two different phases of the spin chain.
   - It involves mapping the system to quantum circuits, optimizing these circuits, executing time evolution circuits, and analyzing the results. The lab provided insights into the Heisenberg model, its phases, and how to simulate its dynamics using Qiskit.

Each lab is accompanied by detailed comments and explanations to ensure the material is accessible and understandable.

## Certificate of Completion

I successfully completed the Qiskit Global Summer School, and you can view my certificate [here](https://www.credly.com/badges/93a9778b-567b-456b-9b66-c7f26323a1fa/public_url).

