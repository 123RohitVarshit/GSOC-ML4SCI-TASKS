# Task XI: Quantum Multi-Layer Perceptron (QMLP)

This directory contains the implementation for **Task XI** of the ML4SCI QMLHEP challenges. The objective of this task is to design, implement, and train a Parameterized Quantum Circuit (PQC) based Multi-Layer Perceptron (Quantum MLP).

## Overview
A Quantum MLP leverages the principles of quantum mechanics to process data. In this project, we replace classical dense layers with parameterized quantum layers to perform classification tasks typical in High-Energy Physics (HEP). 

### Key Features
- **Data Encoding**: Mapping classical data into quantum states using angle or amplitude embedding.
- **Parameterized Layers**: Variational quantum layers with trainable rotation and entanglement gates.
- **Measurement**: Extracting classical values from the quantum state to compute loss and gradients.
- **Hybrid Optimization**: Using hybrid quantum-classical optimization loops to update circuit parameters.

## Files
- `UPDATED_PQC_MLP.ipynb`: The primary notebook demonstrating the construction, training, and evaluation of the QMLP. 

## How to Run
Open `UPDATED_PQC_MLP.ipynb` in your preferred notebook environment. Since simulating quantum circuits can be computationally intensive, running this on a machine with decent resources or Google Colab is recommended.
