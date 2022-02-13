# Quantum Computing Experiments

### My first circuit
This circuit contains two qubits. One qubit (q0) is superimposed with itself using Hadamard gate. CNOT gate is used to entangle both qubits q0 (controlled qubit) and q1 (target qubit). Both qubits are observed, which leads to disrupting their wave (probable/uncertain) nature, to measure a fixed value. We ran this 1024 times on Qasm simulator which instantly generated the results (left side of the image below) showing superimposed (520 times in state |00>, 504 times in state |11>) nature of both qubits since they are entangled. 

![My first circuit](./docs/My_first_circuit.png)

- Learn from https://quantum-computing.ibm.com/ about building the quantum circuit shown above.
- Refer notebooks/HelloQuantum.ipynb notebook to build and execute above circuit in Python programming.