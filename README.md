# Quantum Machine Learning for Drug Efficiency Prediction

A quantum machine learning implementation using Variational Quantum Classifier (VQC) to predict pharmaceutical drug effectiveness levels.

## 🎯 Overview

This project demonstrates the application of quantum computing in pharmaceutical research by leveraging quantum machine learning algorithms to predict drug efficiency. The model classifies drugs into three effectiveness categories: "Not Effective", "Effective", and "Highly Effective" using quantum circuits and variational optimization techniques.

## 🔬 Methodology

The quantum machine learning approach offers potential advantages over classical methods, including:
- Enhanced pattern recognition through quantum superposition
- Reduced computational complexity for certain optimization problems
- Novel feature mapping capabilities in quantum Hilbert spaces

## 🚀 Implementation Pipeline

### 1. Environment Setup
- **NumPy**: Numerical computations and array operations
- **Qiskit**: Quantum computing framework and circuit simulation
- **VQC modules**: Variational Quantum Classifier components

### 2. Quantum Feature Mapping
Transforms classical input data (drug properties) into quantum states using quantum feature maps. This encoding allows the quantum circuit to process classical information in quantum superposition states.

### 3. Variational Ansatz Design
- **Architecture**: Parameterized quantum circuit with alternating layers
- **Gates**: Rotation gates (RY, RZ) for single-qubit operations and controlled-Z gates for entanglement
- **Structure**: Configurable repetition layers for increased expressivity
- **Purpose**: Creates the trainable component of the VQC model

### 4. Quantum Backend Configuration
- **Simulator**: Quantum state vector simulator
- **Shots**: Configurable measurement repetitions for statistical accuracy

### 5. Classical Optimization
- **Algorithm**: Gradient-based optimizer (e.g., COBYLA, SPSA)
- **Objective**: Minimize cost function through parameter optimization
- **Convergence**: Iterative parameter updates until optimal solution

### 6. Model Training
- **Data Encoding**: Drug effectiveness labels mapped to numerical values (0, 1, 2)
- **Training Process**: Variational parameter optimization using quantum-classical hybrid approach
- **Cost Function**: Cross-entropy loss for multi-class classification

### 7. Model Evaluation
- **Testing**: Performance assessment on unseen drug data
- **Metrics**: Classification accuracy, confusion matrix analysis
- **Validation**: Comparison with classical machine learning baselines

## 📊 Data Structure

```
Drug Effectiveness Mapping:
├── "Not Effective"    → Label 0
├── "Effective"        → Label 1
└── "Highly Effective" → Label 2
```

## 🛠️ Getting Started

### Prerequisites
```bash
pip install qiskit
pip install numpy
pip install matplotlib
```

### Usage
1. Clone the repository
2. Install dependencies
3. Prepare your drug dataset with relevant features
4. Configure quantum circuit parameters
5. Run the training script
6. Evaluate model performance



## 📚 Scientific Context

This work contributes to the emerging field of quantum machine learning in drug discovery, exploring how quantum computing principles can potentially accelerate pharmaceutical research and development processes.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests, report bugs, or suggest improvements to advance quantum machine learning applications in healthcare.

