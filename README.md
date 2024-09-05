# QVNE
## Virtual Network Embedding Problem With Quantum Optimization (Qiskit's VQE)

_This is my B.Sc. degree project for electrical engineering at the University of Tehran_


#### Note: If you just want to use the QVNE class and do not wish to know how it works under the hood, there are three examples included at the end of the note to show you how you can use the class, ordered from hard to easy.

__Required packages are listed in *requirements.txt* file__


* The main object being built in this note is named QVNE; you can use QVNE to:
  1. randomly construct two graphs (named Subtrate Network and Virtual Network), and
  2. map the Virtual Network to the Substrate Network.

* The mapping is divided into two sub-tasks; Node Mapping and Link Mapping.
  1. Node mapping is done by classical algorithms.
  2. Link mapping has two options: classical method (by CPLEX) or quantum-classical method (by Qiskit's QAOA)

* I use IBM's Qiskit module to simulate the quantum circuit. 
[This tutorial](https://qiskit.org/documentation/tutorials/optimization/7_examples_vehicle_routing.html) specially helped me in writing the code.

#### Last edit of the code: July 11, 2022

## Apache-2.0 License
Copyright 2024 Yasaman Parhizkar

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
