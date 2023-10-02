# quantum

If you are a newbie I hightly recommend that you watch these videos first:
1. Quantum Computers Explained – Limits of Human Technology by Kurzgesat - In a Nutshell   https://www.youtube.com/watch?v=JhHMJCUmq28 
2. Quantum Computers, Explained With Quantum Physics by Quanta Magazine    https://www.youtube.com/watch?v=jHoEjvuPoB8
3. The Map of Quantum Computing | Quantum Computers Explained by Domain of Science  https://www.youtube.com/watch?v=-UlxHPIEVqA

It is important that you understand three things in order to comprehend quantum computing:
1. Superposition: Refers to the unique property of quantum bits or qubits that allows them to exist in multiple states simultaneously. (Being the states 1 or 0)
2. Entanglement:
3. Interference: 

**Remember a Qubit is really described by a Quantum Wavefunction. 

Quantum algorithms:

*Shor's algorithm:

*Grover's algorithm: Search algorithm.
*(QAOA) Quantum Approximate Optimization Algorithm: Heuristic algorithm
*(VQE) Variational Quantum Eigen: Hybrid algorithm.


Name	Function	Application	Proven	Speedup
Shor	Factorization	Break the RSA encryption	Yes	Super Polynomial
Grover	Search	Bitcoin mining, quadratic speedups for NP hard problems	Yes	Polynomial
HHL (Harrow-Hassidim-Lloyd)	Solve linear equations	Machine Learning, PDE's (Partial Differential Equations)	Yes	Super Polynomial
VQE (Variationl Quantum Eigensolver)	Find molecular ground state	Manufacturing, material science	No	Unknown
QAOA (Quantum Approximate Optimization Algorithm)	Find Hamiltonian ground state	Discrete Optimization Problems	No	Unknown
QSVT (Quantum Singular Value Transformation)	Linear Algebra Transformations	Many Problems, Including Signal Processing	Yes	Depends on Application
QML (Quantum Machine Learning)	Machine Learning	Machine Learning	Partially	Depends on Algorithm
![image](https://github.com/daniperil/quantum/assets/24758279/2ae49988-a155-4877-8d27-53125f2453c4)



Simulations: 

Why are we actually interested in simulation? Simulations of quantum systems can help examine properties, structure, and behaviour of something like a molecule. This way they can help us, for example, develop new and more efficient materials for batteries leading to more efficient mobility. Understand the chemical processes involved in the process of fertilizer production could support finding a process that uses way less energy. And for drug research, scientists would be able to investigate these drugs without actually creating them in a lab synthetically.

And why is simulating something like a molecule so hard to do? Molecules are made up of atoms like Hydrogen (H), Oxygen (O), Nitrogen (N) and so on. Those atoms are themselves made up of protons, neutrons and electrons. In order to simulate a molecule, we need to think about every single electron, their position, their interaction among each other and any forces acting on the molecule. Storing all of this requires a huge amount of computer memory
"Nature isn't classical, dammit, and if you want to make a simulation of nature, you'd better make it quantum mechanical. 
Richard Feynman (1981), physicist and Nobel Prize laureate (1965)

Optimization:

We read and hear, that quantum computing will be useful at a range of tasks. One of them is optimization, which is the problem of finding the best solution from all possible solutions. Optimization problems are common in business. For example, you might want to find the optimal portfolio of financial assets (lowest cost, highest return, least risk, or some combination of these factors that you care about). Or you might want to figure out the best way to deliver packages. In this case, “best” might mean shortest time or lowest fuel cost or some combination of the two. To get a feeling for why optimization problems are a huge challenge for conventional computers, let's consider a particular optimization problem...

Machine Learning:

Essentially in machine learning, the computer learns about specific parameters. These can be the number of red, blue, green or yellow dots in our hexapawn game. But this can also be the rotations of gates in a quantum circuit. This is one way to do quantum machine learning. Quantum machine learning is an active field of research, so we expect new approaches popping up in the future.

One area where QML is definitely ahead is when we look problems where the data is not from a classical but quantum in itself. Then a quantum computer is here to shine as recently demonstrated by researchers in an experiment that analyzed quantum data from the physical world.
