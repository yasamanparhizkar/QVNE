# QVNE
## Virtual Network Embedding Problem With Quantum Optimization (Qiskit's VQE)

_This is my degree project for BSc in electrical engineering at the University of Tehran_


#### Note: If you just want to use the QVNE class and do not wish to know how it works under the hood, there are three examples included at the end of the note to show you how you can use the class, ordered from hard to easy.


* The main object being built in this note is named QVNE; you can use QVNE to:
  1. randomly construct two graphs (named Subtrate Network and Virtual Network), and
  2. map the Virtual Network to the Substrate Network.

* The mapping is divided into two sub-tasks; Node Mapping and Link Mapping.
  1. Node mapping is done by classical algorithms.
  2. Link mapping has two options: classical method (by CPLEX) or quantum-classical method (by Qiskit's VQE)

* I use IBM's Qiskit module to simulate the quantum circuit. 
[This tutorial](https://qiskit.org/documentation/tutorials/optimization/7_examples_vehicle_routing.html) specially helped me in writing the code.


#### Last edit: June 11, 2021
