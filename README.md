# QVNE
## Virtual Network Embedding Problem With Quantum Optimization (Qiskit's QuadraticProgram)

_This is my degree project for BSc in electrical engineering at the University of Tehran_


#### Note: If you just want to use the QVNE class and do not wish to know how it works under the hood, there are three examples included at the end of the note to show you how you can use the class, ordered from hard to easy.


* The main object being built in this note is name QVNE; you can use QNVE to:
  1. randomly construct two graphs (named Subtrate Network and Virtual Network), and
  2. embed the Virtual Network into the Substrate Network.

* The embedding is divided into two tasks; Node Mapping and Link Mapping.
  1. Node mapping is done by classical algorithms.
  2. Link mapping is done by a quantum-classical algorithm.


#### Last edit: June 3, 2021
