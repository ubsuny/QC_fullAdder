# Implementing a full adder and phase calculator on a Quantum Computer 


## Introduction

The code in Adder.ipynb serves as a full adder that can calculate 1+1+1=3 on a quantum computer, and Phase.ipynb correctly calculates the input angle.

## Setup


1. I made an account on IBM qiskit (https://quantum-computing.ibm.com/composer/files/new?initial=N4IgdghgtgpiBcIASB1AxARngAgGIFcAbQ7CAEzJgCdsAKDAagCYBeAZgEpsQAaEARwgBnKAhAB5AAoBRAHIBFAIIBlALLYmAOgAMAbgA6YAJZgAxoXyVs%2BgTEJGARhk0nTNg2EP8qMAObZ%2BAG0AVgBdD1Mff1MQ8MNDHyEYABcAwO04sESUtIxM7NSgpkzTAA80jJ4gthLyoLyqwJqIusDixubDUzKK0MaGoIAWEp6ivqDKoZHWgbbxwOGPWGF8HzSa7ABaAD5sGM6wZaFVmDThrd2Yxd4QSiFIowAHZKMAezAxEABfIA)
2. I used the IBM Quantum Composer to graphically assemble a circuit with 3 input qubits that can be initialized to 0 or 1, and the circuit computed its addition.
3. I then recreated this circuit in a Jupyter notebook using the IBM Quantum Lab, and ran it on ibm_quito, and verified it works correctly.
4. I then made another circuit in IBM Quantum Composer to calculate the real part of phase for the phase calculator and then did the same for the imaginary part.
5. I then recreated these circuits in the IBM Quantum Lab Jupyter notebook, got the x and y counts, normalized them and then used the atan2() function to get the phase again.
6. To see this in action, just open the Adder.ipynb and Phase.ipynb files and run them on your machines!

## Results

my code could count to three for the following cases:

1. 1+1+1=3

my code could get the result for phase of π/3

## Discussion

My adder got the accurate sum with a prabability of 0.492, and it got pretty close (1.0188202912233635) to the value of π/3 (= 1.047197551196597) when run on a quantum computer. It is not fully accurate because this is not an ideal problem to be solved on a quantum conputer.

## Outlook

The Adder.ipynb can be expanded further to calculate additions of more than 3 qubits, but I could not implement it.
