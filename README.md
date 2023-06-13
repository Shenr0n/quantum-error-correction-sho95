# Quantum Error Correction with Shor Code

•	Assembled encoding and correction quantum circuits for bit-flip and phase-flip errors in qubits using Python 3 and Qiskit's quantum logic gates on IBM Quantum Lab, using superposition and entanglement properties.

• Constructed and visualized the Sho95 (Shor code) circuit for error correction, and simulated the errors based on probabilities.

• Analyzed performance of Shor code and uncorrected qubits, and visualized the results using Matplotlib based on state fidelity property of quantum states plotted against increasing probability of errors to verify the accuracy after Quantum state measurements.

## Information

* `Quantum Error Correction` - [Wiki](https://en.wikipedia.org/wiki/Quantum_error_correction)

## Tech-stack
* `Qiskit` - Open-Source SDK for Quantum Development  [Qiskit Website](https://qiskit.org/)
* `Matplotlib` - Comprehensive library for creating static, animated, and interactive visualizations in Python [Matplotlib Link](https://matplotlib.org/)
* `Python 3` - Programming Language [Python Website](https://www.python.org/)
* `IBM Quantum Lab` - Online platform for cloud-based quantum computing services provided by IBM Quantum[IBM Quantum Lab Website](https://lab.quantum-computing.ibm.com)


### Running the project 
* Create an account on IBM quantum lab and upload the notebook
* All required libraries will be imported and the notebook can be run without any changes

## Outputs and Observations

* Phase-flip encoding and correction

![pic1](https://user-images.githubusercontent.com/20452759/235585985-8381b79c-5ca0-44fe-81ce-810b6f7b573a.png)

* Bit-flip encoding and correction

![pic2](https://user-images.githubusercontent.com/20452759/235585991-338b8395-5449-4a25-9286-900d9c08a769.png)

* The error correction of bit-flips and phase-flips can be observed in the notebook with the plotted bloch spheres

* Shor code's encoding circuit (Combination of bit-flip and phase-flip encoding)

![pic3](https://user-images.githubusercontent.com/20452759/235586024-f40491c5-3985-4a86-9d2a-c5759b5f1d91.png)

* Shor code's correction circuit (Combination of bit-flip and phase-flip corrections)

![pic4](https://user-images.githubusercontent.com/20452759/235586034-0421f861-b2f7-4d27-91ef-7266c947ea2c.png)

* Sho95 Circuit with simulated error. The result is that the initial and final state of qubits remain the same

![pic5](https://user-images.githubusercontent.com/20452759/235586043-72c366c8-6504-45d3-9ea2-77333bd2838f.png)

* Sho95 with errors in 6 qubits. As the number of errors/ probability of error occuring increases, the performance of Shor code to correct them decreases. Here the initial and final states are different


![pic6](https://user-images.githubusercontent.com/20452759/235586059-65045361-e3a3-43f1-8baa-6c6773195e7f.png)

* Sho95 with very high probability of errors. Here the circuit fails to correct errors

![pic8](https://user-images.githubusercontent.com/20452759/235586069-f6862727-5285-46a1-bc94-6ccfb05c18df.png)

* Graph of average state fidelity against increasing probability of errors for Shor code and uncorrected circuit

![pic9](https://user-images.githubusercontent.com/20452759/235586086-f8b1663d-3bbf-4330-b934-3f366c931e04.png)
