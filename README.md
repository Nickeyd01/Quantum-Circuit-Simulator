# Quantum-Circuit-Simulator
Quantum Circuit Simulator (Python) for a subset of QASM programs. 14 QASM programs used for testing.

This Quantum Circuit simulator allows us to run QASM files. Qasm files allow to to describe quantum circuits and algorithms on current quantum computers.

This project was part of a class at UCLA but can be extended to any set of QASM files by extending the gates that are available.

The simulator is written in Python. There are different gates defined in the STATE class, these gates include Hadamard,T, CNOT, D and X. Another class is defined to keep track of tensor operations, coefficients, and states. 

The simulate function allows to read in the files and its associated gates. If new file is added with larger gate set, function has to be adapted to take these into account. 

Main function allows to read in different files from folder.
