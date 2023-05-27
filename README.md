# Using-Quantum-Machine-Learning-to-Predict-Drug-Efficiency-

This is the first version of a quantum machine learning I created to predict Drug Efficiency.

The steps to building this model are :

1/Import the modules :NumPy for numerical operations, Qiskit for quantum computing, and specific modules for VQC.

2/ Define the feature map : We will use to transform our input data into quantum state

3/Define the variational form (ansatz): A parameterized quantum circuit used for the trainable part of the VQC model. It consists of alternating rotation gates
(ry, rz) and entanglement gates (cz). The circuit is repeated for a specified number of repetitions (reps).

4/Define the quantum instance: The backend (simulator we will use )

5/Define the classical optimizer: Used to find optimal parameters for the variational form.

6/Define the VQC model( Variational Quantum Classifier)

7/Define the training data & labels : Map "Not Effective" to 0, "Effective" to 1, "Highly Effective" to 2

8/Train the model

9/Test the model
