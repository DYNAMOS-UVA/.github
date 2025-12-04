# DYNAMOS - Middleware for data exchange systems
This is a hub of projects related to DYNAMOS (Dynamically Adaptive Microservice-based OS). 


## Repositories
- [DYNAMOS](https://github.com/DYNAMOS-UVA/DYNAMOS) (main project):
A microservice-based proof-of-concept implementation of the DYNAMOS middleware for dynamically adaptive data-exchange systems. This repository contains the core services, deployment manifests and example archetypes used during the thesis work and demos. 
    - **Original authors:** Jorrit Stutterheim, Aleandro Mifsud 

- [Scattered Directive](https://github.com/DYNAMOS-UVA/Scattered-Directive)
is an automated and reproducible framework to deploy the DYNAMOS digital data marketplace on research testbeds (e.g., FABRIC). It automates setup steps such as node reservation, configuration and deployment of DYNAMOS archetypes so researchers can reproduce experiments without manual provisioning. The repository includes profiles, automation scripts and an example archetype for Vertical Federated Learning that demonstrates shared execution via a Trusted Third Party (TTP).
    - **Original author:** Jake Jongejans 

- [Energy Efficient DYNAMOS](https://github.com/DYNAMOS-UVA/EnergyEfficiency_DYNAMOS)
This fork focuses on energy-efficiency optimizations for DYNAMOS archetypes. The work documents an energy-reporting pipeline, identifies candidate optimizations (e.g., request caching, data compression), implements selected optimizations, and validates results in both local Docker and distributed Kubernetes deployments (including FABRIC). Key findings are that caching often reduces energy and execution time significantly, while compression can introduce compute overheads. The repo contains measurement scripts, experiment configurations and analysis artifacts used for the thesis.
    - **Original author:** Collin Poetoehena

- [FL disagreement resolution](https://github.com/DYNAMOS-UVA/fl-disagreement-resolution)
A federated learning simulation and orchestration system that implements multi-track disagreement resolution for client-level exclusions. It addresses scenarios where not all clients mutually agree to collaborate: the system creates isolated model-update “tracks” per disagreement preference to enforce client-level exclusion and prevent cross-contamination. The project contains simulation code, visualization tools for track contributions over time, and material used for evaluation in the thesis and related publications.
    - **Original author:** Daan Rosendal


## [Publications](https://github.com/DYNAMOS-UVA/DYNAMOS/tree/main/docs/papers) 

1. Stutterheim, Jorrit, Aleandro Mifsud, and Ana Oprescu. **"Dynamos: dynamic microservice composition for data-exchange systems, lessons learned."** 2024 IEEE 21st International Conference on Software Architecture Companion (ICSA-C). IEEE, 2024.
2. Dalgkitsis, Anestis, et al. **"Secure Collaborative Model Training with Dynamic Federated Learning in Multi-Domain Environments."** SC24-W: Workshops of the International Conference for High Performance Computing, Networking, Storage and Analysis. IEEE, 2024.

<!--
3. TODO: INDIS 2025 publication upload to arxiv?
-->



## Upcoming (accepted for publication)
1. Jake Jongejans, Alexandros Koufakis, and Ana Oprescu. **"Vertical Federated Learning on Scattered Directive:
Enforcing Policies on VFL Workflows"** 2025 IEEE Big Data 
2. Daan Rosendal, and Ana Oprescu **"A Taxonomy and Resolution Strategy for
Client-Level Disagreements in Federated Learning"** 2025 IEEE Big Data
3. Alexandros Koufakis, Collin Poetoehena, Tom van Engers, and Ana Oprescu. **"An Empirical Study of Energy Efficiency Monitoring for Complex
Container-Based Systems"**, 10th International Workshop on Green and Sustainable Software (GREENS’26)



## Demonstrations & More Material: (reverse chronologically)
- (Nov 2025) SC 2025
- RENCI webinar 
- SC 2024: add CCI newspost link 
- [SuperComputing demonstration 2023: Dynamos: Dynamically Adaptive Microservice-based OS](../Demonstration_material/SC_2023/SC2023.md)



(TODO: make folders for each and put material there)


