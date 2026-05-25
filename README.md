# Pasqal (pasqal)

Pasqal is a French neutral-atom quantum computing company headquartered in Palaiseau, France and co-founded in 2019 by 2022 Physics Nobel Laureate Alain Aspect. Pasqal builds commercial-grade neutral-atom quantum processors (the Fresnel QPU family) that use arrays of laser-trapped Rydberg atoms to run both analog and digital quantum programs, and packages them as on-premise systems and as Pasqal Cloud Services — a pay-as-you-go quantum computing platform also distributed through Google Cloud, Microsoft Azure Quantum, OVHcloud, and AWS partners. The developer surface is anchored by the open-source Pulser SDK, the pasqal-cloud Python SDK, and the Pasqal Cloud Services REST API.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/pasqal/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

Quantum Computing, Neutral Atom, Quantum, QPU, Rydberg, Pulse-Level Control, Analog Quantum, Digital Quantum, HPC, Optimization, Quantum Machine Learning, Quantum Simulation, France

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### Pasqal Cloud Services API
REST API for Pasqal Cloud Services — submit and manage quantum Batches and Jobs on Pasqal Fresnel QPUs and on emulator backends (EMU-FREE, EMU-TN, EMU-MPS, EMU-SV), query Devices and Device Specifications, run custom Workloads, and manage Projects, Members, Contracts, Credit Pools, and Monthly Credit Consumption. Endpoints are organized under `/api/v1` and `/api/v2`. Authentication is Auth0-based.

**Human URL:** [https://docs.pasqal.com/cloud/](https://docs.pasqal.com/cloud/)

- [Documentation](https://docs.pasqal.com/cloud/)
- [API Reference](https://docs.pasqal.com/cloud/api/)
- [Portal](https://portal.pasqal.cloud/)
- [pasqal-cloud Python SDK](https://github.com/pasqal-io/pasqal-cloud)
- [Authentication](https://docs.pasqal.com/cloud/usage/authentication/)

### Pulser SDK
Apache-2.0 open-source Python framework for composing, simulating, and executing pulse sequences on neutral-atom quantum devices. Supports digital quantum computing and analog quantum simulation; ships with `pulser_simulation` (QuTiP-based emulation); integrates with `pasqal-cloud` via `pulser-pasqal`. Current release v1.8.0 (May 2026).

**Human URL:** [https://pulser.readthedocs.io](https://pulser.readthedocs.io)

- [Documentation](https://pulser.readthedocs.io)
- [GitHub Repository](https://github.com/pasqal-io/Pulser)
- [PyPI](https://pypi.org/project/pulser/)

### Qadence SDK
Higher-level digital-analog quantum programming interface for writing variational quantum programs with tunable qubit interactions on neutral-atom hardware. Ecosystem includes qadence-libs, qadence-protocols, qadence2-core/-ir/-expressions/-platforms, pyqtorch (PyTorch state-vector simulator), and horqrux (JAX simulator).

**Human URL:** [https://pasqal-io.github.io/qadence/](https://pasqal-io.github.io/qadence/)

- [GitHub Repository](https://github.com/pasqal-io/qadence)
- [PyPI](https://pypi.org/project/qadence/)

### Quantum Evolution Kernel (QEK)
Open-source graph machine learning library that uses quantum-driven similarity metrics derived from neutral-atom dynamics to build graph kernels for classification and regression.

- [GitHub Repository](https://github.com/pasqal-io/quantum-evolution-kernel)

### QUBO Solver
Quadratic Unconstrained Binary Optimization solver library combining classical heuristics with quantum and quantum-inspired approaches on Pasqal neutral-atom hardware.

- [GitHub Repository](https://github.com/pasqal-io/qubo-solver)

### Maximum Independent Set Solver
MIS solver library exploiting the natural mapping of MIS onto Rydberg-blockade dynamics of neutral-atom QPUs.

- [GitHub Repository](https://github.com/pasqal-io/maximum-independent-set)

### QoolQit SDK
Python package for simplified algorithm development in the Rydberg Analog Model on neutral-atom hardware — a more approachable layer above Pulser for analog quantum algorithm authors.

- [GitHub Repository](https://github.com/pasqal-io/qoolqit)

### Pasqal Emulators (EMU-MPS, EMU-SV)
PyTorch-based GPU-accelerated emulator monorepo housing EMU-MPS (matrix-product-state, 60-100 qubits) and EMU-SV (high-precision state-vector). Available locally and as Pasqal Cloud Services backends.

- [GitHub Repository](https://github.com/pasqal-io/emulators)

## Features

- Fresnel QPU — Pasqal's commercial neutral-atom quantum processor based on arrays of laser-trapped Rydberg atoms, scaling toward 1000+ atoms
- Dual analog and digital quantum computing on a single neutral-atom architecture
- Pulser open-source SDK (Apache-2.0) for pulse-level / analog programming
- Pasqal Cloud Services REST API for batches, jobs, workloads, devices, projects, members, billing
- pasqal-cloud Python SDK wrapping the Cloud Services REST API
- Qadence digital-analog programming interface with PyTorch (pyqtorch) and JAX (horqrux) backends
- Pulser Studio no-code visual programming environment
- EMU-MPS and EMU-SV GPU-accelerated emulators (60-100 qubits)
- Quantum Evolution Kernel (QEK) graph machine learning library
- QUBO and Maximum Independent Set application libraries mapped to Rydberg-blockade dynamics
- Auth0 authentication with username/password, token-provider, and Auth0TokenProvider flows
- Credits-based pay-as-you-go billing via Credit Pools and Monthly Credit Consumption endpoints
- NVIDIA CUDA-Q integration for hybrid quantum-HPC workflows
- Multi-cloud distribution through Google Cloud, Microsoft Azure Quantum, OVHcloud, and AWS partners
- On-premise deployment of commercial-grade neutral-atom quantum computers
- May 2026 industry-first demonstration of neutral-atom logical qubits outperforming physical qubits

## Use Cases

- Combinatorial optimization (QUBO, MIS) for logistics, smart charging, routing, scheduling
- Quantum machine learning via graph kernels (QEK) and variational models (Qadence)
- Quantum chemistry and materials simulation via analog Hamiltonian methods
- Drug discovery and molecular docking (partnership with True Nexus)
- Finance and risk modeling
- Smart charging and energy-grid optimization
- Hybrid quantum-HPC workloads with CINECA, GENCI, EuroHPC centers
- Space mission optimization (smo-qubo)

## Integrations

NVIDIA CUDA-Q, Microsoft Azure Quantum (pulser-azure), Google Cloud Marketplace, AWS partners, IBM partnership, OVHcloud, Atos/Eviden myQLM (Pulser-myQLM), CINECA / GENCI / EuroHPC supercomputing centers, Saudi Aramco MENA platform.

## Solutions

- Pasqal Cloud Services — pay-as-you-go cloud access to Fresnel QPUs and emulators
- On-premise neutral-atom quantum computers for customer facilities
- Pulser Studio — no-code visual programming environment
- Quantum application libraries — QEK, QUBO-Solver, MIS, smo-qubo, Molecular-Docking

## Common

- [Portal](https://www.pasqal.com)
- [Documentation](https://docs.pasqal.com)
- [Getting Started](https://docs.pasqal.com/cloud/usage/)
- [Sign Up / Console](https://portal.pasqal.cloud/)
- [Pulser Studio (Sandbox)](https://studio.pasqal.cloud/)
- [API Reference](https://docs.pasqal.com/cloud/api/)
- [Authentication](https://docs.pasqal.com/cloud/usage/authentication/)
- [Pricing — Quantum Computing as a Service](https://www.pasqal.com/quantum-computing-as-a-service/)
- [Blog](https://www.pasqal.com/blog/)
- [News](https://www.pasqal.com/news/)
- [Careers](https://www.pasqal.com/careers/)
- [Contact](https://www.pasqal.com/contact-us/)
- [Pasqal Community (Forum)](https://community.pasqal.com/)
- [GitHub Organization](https://github.com/pasqal-io)
- [LinkedIn](https://www.linkedin.com/company/pasqal/)
- [Twitter](https://twitter.com/Pasqalio)
- [YouTube](https://www.youtube.com/@Pasqal)
- [Terms of Service](https://www.pasqal.com/terms-of-use/)
- [Privacy Policy](https://www.pasqal.com/privacy-policy/)

## Maintainers

- **Kin Lane** — [API Evangelist](https://apievangelist.com) — kin@apievangelist.com — [@apievangelist](https://twitter.com/apievangelist)
