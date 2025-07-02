### The Goal:

In this repository, we implement a quantum calculator. We design a quantum circuit $U$ with the property that:

$$U \Ket{x}_d \Ket{y}_d \Ket{0}_d \Ket{z}_1 = \begin{cases} \Ket{x}_d \Ket{y}_d \Ket{x + y \mod 2^d}_d \Ket{z}_1 \text{ if } z=0 \\ \Ket{x}_d \Ket{y}_d \Ket{x \cdot y \mod 2^d}_d \Ket{z}_1 \text{ if } z=1 \end{cases} $$

Note that the circuit has some additional ancillary qubits.

Use the function QuantumCalculator(d) to get a circuit with the above mentioned properties. 
