# Implementing a full adder on a Quantum Computer and a phase shift measurement scheme

## Introduction
This project includes the implementation of a Full Adder and Phase Shift Measurement Scheme on IBMs Quantum Computer using Qiskit.

The Full Adder uses the example of 1+1+1 = 3.

The Phase Shift Measurement Scheme is able to determine the phase that a qubit underwent after being split and recombined by a Hadamard gate. The example used is pi/3.

## References 
1. https://qiskit.org/textbook/ch-states/representing-qubit-states.html
2. https://qiskit.org/textbook/ch-demos/chsh.html
3. https://quantum-computing.ibm.com/composer/docs/iqx/guide/introducing-qubit-phase
4. https://www.ibm.com/quantum-computing/quantum-computing-at-ibm/
All references are from qiskit documentation or IBMs quantum computer documentation.
## Setup

1. Make an account with IBMs quantum computer found in Reference 4.
2. The Jupyter Notebooks included in this repository link to IBMs quantum computer. Download them.
3. Upload the files to IBMs Quantum Lab and run the Notebook.
4. The default quantum computer used is *quito*. This can be changed/

## Results

The Full Adder worked for the following case.

1. 1+1+1+1=3

I could not count to three for the following cases:

1. 1+2=3

my code could count to four for the following cases:

1. 1+1+1+1=4

If expansion is needed, additional qubits are required.

The Quantum Phase Measurement Calculator uses the example of $\frac{\pi}{3}$.

## Discussion

My code could compute 1+1+1=3, however it took the QC 13 seconds and out of 8192 shots it did it wrong in a majority of the cases. So it might be not the best choice for this task. However, they are awesome for optimizing the [traveling salesman problem](https://xkcd.com/285/).

My code for the phase measurement circuit was typically accurate to within 10%.

## Outlook

The Full Adder can be expanded in many directions, such as :

Adding another base qubit and another carry qubit for the case of (1+1+1+1) = 4

Adding an additional base qubit to account for the sign could allow for (-1+1) = 0
