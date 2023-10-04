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

![image](https://github.com/daniperil/quantum/assets/24758279/2ae49988-a155-4877-8d27-53125f2453c4)

Steps to build Quantum Applications:
1. Map the problem to an abstract mathematical formalism
2. Use the algorithm to translate the abstract problem to quantum logic
3. Implement the quantum logic into concrete quantum gates
4. Review the results and modify the implementation.

In quantum computing, an "oracle function" refers to a specific type of quantum operation. Oracles are used to encode problem-specific information into the quantum state and provide a way for the quantum algorithm to access and manipulate this information. (The Oracle is defined in the Expression section for the Classiq IDE)

**The size is the number of qubits we allocate to encode the number. 

The Oracle has the effect of tagging the correct Quantum States. 
Amplitude Amplification: Amplify the amplitude of tagged States while suppressing others.

In the Right Hand side in the box "Number of Repetitions" is where you put the amount of times you want Amplitude Amplification to be repeated. 

Information about the AerSimulatior: https://qiskit.org/ecosystem/aer/stubs/qiskit_aer.AerSimulator.html

The hardware for quantum computing must contain at least one single qubit gate and one two qubit gate. Name is qpu.
Josephson effect is a phenomenon that occurs when two superconductors are placed in proximity, with some barrier or restriction between them.
The Josephson effect produces a current, known as a supercurrent, that flows continuously without any voltage applied, across a device known as a Josephson junction (JJ). These consist of two or more superconductors coupled by a weak link. The weak link can be a thin insulating barrier (known as a superconductor–insulator–superconductor junction, or S-I-S), a short section of non-superconducting metal (S-N-S), or a physical constriction that weakens the superconductivity at the point of contact (S-c-S).

Circuit depth is the number of gates performed on a qubit.

Because gate are not perfect each gate operation introduces errors. 

These errors are called Noise.

Two qubit gates typically have more Noise than one qubit gate.

The current state of quantum computing[1] is referred to as the noisy intermediate-scale quantum (NISQ) era,[2] characterized by quantum processors containing up to 1000 qubits which are not advanced enough yet for fault-tolerance or large enough to achieve quantum supremacy.


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
