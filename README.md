**Quantum Teleportation Simulation using Qiskit AER Simulator**
This is an implementation of the Quantum Teleportation protocol using Qiskit's AER simulator. 

Quantum teleportation is a protocol that transfers an unknown quantum state from one party (Alice) to another (Bob) without moving the physical particle. It uses one qubit carrying the unknown state plus an entangled pair shared between Alice and Bob (three qubits total). In this protocol, Alice performs a joint (Bell) measurement on her two qubits, producing two classical bits which she sends to Bob, those classical bits tell Bob which Pauli corrections, if any, to apply to his half of the entangled pair, after which Bob’s qubit is in the original state and Alice’s initial qubit state is irreversibly destroyed.

The implementation's  outputs are:
1. Quantum circuit.
2. Expected and actual measurement of Bob's qubit after telepotation.
3. Fidality value: A number between 0 and 1 that quantifies how closely the teleported state matches the original, 1.0 indicates perfect agreement and 0.0 indicates no overlap.
The user selects a single-qubit input state and the number of shots.