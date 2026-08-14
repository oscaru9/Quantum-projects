# Quantum Physics Research & Development Portfolio

Welcome to my central quantum research repository. This space serves as a portfolio displaying toy models of the projects I have developed throughout my academic journey.

## 🎯 Purpose & Scope

This repository presents a collection of computational projects in quantum information and quantum computing. The projects explore quantum dynamics, noise, and quantum error mitigation through numerical simulations and analysis of quantum circuits, with an emphasis on clear, reproducible, and well-structured computational workflows.

---

## 📁 Repository Structure

This repository is organized into 5 main research modules. Detailed documentation, execution scripts, and theoretical backgrounds can be found within each respective folder:

| Module / Folder | Core Topics & Stack | Focus Area |
| :--- | :--- | :--- |
| **`01_Spin_Chains/`** | Julia, Open Systems | Dynamics of Suzuki-Trotter spin chains ($N=8$) and Markovian noise models. |
| **`02_Quantum_Circuits/`** | Qiskit Runtime, Python | Real QPU execution, raw bitstring extraction, and gate-depth error scaling. |
| **`03_Quantum_Error_Mitigation/`** | Julia / Python, Monte Carlo | Probabilistic Error Cancellation (PEC) implementations on toy circuit models. |
| **`04_Hamiltonian_Reproduction/`** | Julia, Numerical Methods | Inverse parameter estimation and numerical Hamiltonian learning pipelines. |
| **`05_Husimi_Phase_Space/`** | Python, Phase Space | Phase-space representations ($Q$-functions) for entanglement classification. |

---

## 🔬 Overview of Modules

### 1. `Spin_Chains`
* **Focus:** Numerical simulation of closed quantum dynamics.
* **Key Features:** Custom Suzuki-Trotter evolution engines.

### 2. `Quantum_Circuits`
* **Focus:** Hardware noise characterization via IBM Quantum processors.
* **Key Features:** Real hardware data retrieval using `SamplerV2`, zero-optimization (`optimization_level=0`) circuit layers, and depth-dependent fidelity decay analysis.

### 3. `Quantum_Error_Mitigation`
* **Focus:** Mitigating hardware noise without additional hardware overhead.
* **Key Features:** Implementation of Probabilistic Error Cancellation (PEC) algorithms targeting generic noise models.

### 4. `Hamiltonian_Reproduction`
* **Focus:** System identification and observable benchmarking.
* **Key Features:** Reconstructing Hamiltonian parameters from simulated measurement outcomes.

### 5. `Husimi_Phase_Space`
* **Focus:** Phase-space methods for multipartite quantum systems.
* **Key Features:** Mapping multi-qubit density matrices $\rho$ onto spin-coherent phase-space representations to visualize state topology.

---

## 📄 License & Usage

This repository is made available for portfolio review and academic demonstration purposes.

