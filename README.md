# QuantumLBM
This repository is about developing Carleman Linearization algorithms for the Quantum Lattice-Boltzmann Method. 

Unlike common collision operators of LBM, the calculation of the collision distribution function does not involve macro quantities (density and velocity). All macro quantities has been decomposed into f_i distribution function, which makes the collision and streaming operators can be rewritten in matrix form, and then becoming more handy for quantum simulation.

## classical_kolmogorov
Classical simulation results about a kolmogorov-like flow. The second order Carleman linearization LBM results has been validated by the exact solution of LBM for one dimension flow. 

## classical_taylor
Classical simulation results about Taylor-Green Vortex. The second order Carleman linearization LBM results has been validated by the exact solution of LBM.

## quantum_kolmogorov
Still developing (Qiskit library)...
