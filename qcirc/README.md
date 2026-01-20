# QCircSim
This project is a lightweight quantum circuit simulation framework written from scratch in Python. 
It supports both statevector and density-matrix backends, explicit noise models (bit-flip, phase-flip,
depolarizing), circuit-level metrics, and interoperability with OpenQASM and Qiskit.

The simulator includes a simple circuit description language (SCL), variational circuit experiments
(VQE-style grid and random search), and a Streamlit-based web UI for interactive exploration and
visualisation.

### Features

- Statevector and density-matrix simulation backends
- Explicit noise models:
  - Bit-flip
  - Phase-flip
  - Depolarizing channels
- Circuit metrics:
  - Purity Tr(ρ²)
  - L1 off-diagonal coherence
  - Pauli expectation values ⟨X⟩, ⟨Y⟩, ⟨Z⟩
- Simple Circuit Language (SCL) with parser and executor
- Variational circuit experiments (VQE-style grid and random search)
- OpenQASM 2.0 export and validation against Qiskit
- ASCII circuit diagrams and operation history tracking
- Streamlit web UI with:
  - Measurement histograms
  - State probabilities
  - Bloch sphere visualisation

