# What are Quantum Computers?
Before discussing what are quantum computers let's see what are classical computers.
* Classical Computers:- In classical computer or generally what we call it as computers we store the the information in the form of binary values (either 0 or 1) and we call those buckets which stores the either of the two values as bits.
    So whatever devices we see today are all classical computers and are made of transistors which stores the information in the form of bits or a stream of bits and operations can be performed on it by the manipulation of those bits. There will be only one state of those bits either 0 or 1 at a time.

* Quantum Computer:- Quantum Computers on the other hand are able to exploit the properties of quantum physics(about which we will discuss as we go further) to perform some computations in a different manner.The quantum property of superposition and entanglement to perform computations are much more efficient as compared to the classical ones.


# Uses of Quantum Computers

# Qubits
    * What is a Qubit?
    * How to simulate a qubit?
    * Different notations of qubits.
    * Bloch Sphere
    * Superposition and Measurement of Qubits

* Qubit :- A qubit is a quantum piece of information used in quantum computing that represents one possible combination of two values.Manipulation of qubits or information stored in qubits is what powers the quantum computers.

* In other words a "qubit" is a **quantum equivalent** of the **classical bit** which can be in either 0 or 1 state or it can be in the state of superposition of state 0 and 1.
See in the figure <br> ![Classical Bits vs Quantum Bits ](https://qph.fs.quoracdn.net/main-qimg-6417dec748f3551b4fe16b8988eafd3c-c "Classical vs Quantum Bits")
Quantum States:- A collection of qubits is known as quantum states.
Superposition:- Two or more qubits can always be added together to produce a valid qubit.Any qubit can be represented as the sum of the two or more other qubits.This is known as superposition.In other words the combinations of the qubits are known as superposition of qubits.
Basis:- The option which we are chosing between the qubit_zero |0> and qubit_one |1> for the combinations or superposition  are know as basis.
There are many differnt options for a basis in quantum computing among which |0> and |1> are the most common basis and if we chose this as our basis to specify our superposition we can specify the percentage of 0 and 1 we want. 
** This basis is also described as the computational basis, the z basis or standard basis.** all of which represents |0> and |1> basis.

### The plus and minus basis
|+> and |-> basis are, just as  |0> and |1> are, in some sense opposites.They can be grouped together as a basis.

|+>  = (|0> +|1>)/sqrt(2)
|-> =  (|0> -|1>)/sqrt(2)

**Note:- The zero |0> and one |1> basis are known as z basis or comupatational basis  as when we go and visualize it on the bloch sphere we can see that it lies on the x axis of the sphere.**


**Note:- The plus |+> and minus |-> basis are known as x basis or diagonal basis  as when we go and visualize it on the bloch sphere we can see that it lies on the x axis of the sphere .**


**Note:- The clockwise and counterclockwise basis are known as y basis or circular basis  as when we go and visualize it on the bloch sphere we can see that it lies on the y axis of the sphere .**


Bloch Sphere:- The bloch sphere is a three -dimensional sphere that has unit radius.

# Quantum States,Quantum Registers and Measurements

* Quantum States and Registers
* Seperable States
* Entanglement
* Quantum Measurement and Entanglement
* Decoherence ,T<sub>1</sub> and T<sub>2</sub>
