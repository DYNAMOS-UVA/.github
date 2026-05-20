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

- [Privacy Enhancing Technologies on Vertical Federated Learning](https://github.com/DYNAMOS-UVA/DYNAMOS-jiyan/tree/thesisJiyan) 
This work intially adjusted the [Scattered Directive](https://github.com/DYNAMOS-UVA/Scattered-Directive) VFL implementation to work on the offline (not FABRIC) DYNAMOS installation. Moreover, this work introduced two optional PET microservices that are integrated in the VFL use case. Specifically the two implemented PETs are an Anonymization service and a Differential Privacy service. <br>
(Note that the repo updates are on the [thesisJiyan branch](https://github.com/DYNAMOS-UVA/DYNAMOS-jiyan/tree/thesisJiyan)))
    - **Original author:** Jiyan Tam 

## [Publications](https://github.com/DYNAMOS-UVA/DYNAMOS/tree/main/docs/papers) 

1. Stutterheim, Jorrit, Aleandro Mifsud, and Ana Oprescu. **"Dynamos: dynamic microservice composition for data-exchange systems, lessons learned."** 2024 IEEE 21st International Conference on Software Architecture Companion (ICSA-C). IEEE, 2024. 
    - [PDF](https://github.com/DYNAMOS-UVA/DYNAMOS/blob/main/docs/papers/architectural/ICSA_DYNAMOS_paper.pdf)
2. Dalgkitsis, Anestis, et al. **"Secure Collaborative Model Training with Dynamic Federated Learning in Multi-Domain Environments."** SC24-W: Workshops of the International Conference for High Performance Computing, Networking, Storage and Analysis. IEEE, 2024.
    - [PDF](https://github.com/DYNAMOS-UVA/DYNAMOS/blob/main/docs/papers/federated_learning/INDIS_2024_Short_Paper_Final_v2_1_45.pdf)
3. Jongejans, Jake, Alexandros Koufakis, and Ana Oprescu. **"Vertical Federated Learning on Scattered Directive: Enforcing Policies on VFL Workflows."** 2025 IEEE International Conference on Big Data (BigData). IEEE, 2025.
    - [link](https://ieeexplore.ieee.org/document/11401076)
4. Rosendal, Daan, and Ana Oprescu. **"A taxonomy and resolution strategy for client-level disagreements in federated learning."** 2025 IEEE International Conference on Big Data (BigData). IEEE, 2025.
    - [link](https://ieeexplore.ieee.org/abstract/document/11401516)
5. Alexandros Koufakis, Collin Poetoehena, Tom van Engers, and Ana Oprescu. **"An Empirical Study of Energy Efficiency Monitoring for Complex Container-Based Systems"**, 10th International Workshop on Green and Sustainable Software (GREENS’26)
    - [PDF](https://github.com/DYNAMOS-UVA/DYNAMOS/blob/main/docs/papers/misc/Energy_efficient_monitoring_GREENS.pdf)


<!-- ### Upcoming (accepted for publication)
1.  -->

## Theses
1. Base DYNAMOS
    - https://scripties.uba.uva.nl/search?id=record_53890
    - Jorrit Stutterheim
2. Scattered Directive 
    - https://scripties.uba.uva.nl/search?id=record_56506 
    - Jake Jongejans
3. Energy Efficient DYNAMOS 
    - https://scripties.uba.uva.nl/search?id=record_55890 
    - Collin Poetoehena 
4. FL Disagreement Resolutions
    - https://scripties.uba.uva.nl/search?id=record_56491 
    - Daan Rosendal

## Demonstrations & More Material:
- [ICT Open 2026](../Demonstration_material/ICT_open/ICT_open_demonstration.md): eFLINT-based policy extraction pipeline for Federated Learning infrastructure 
- [SuperComputing 2025](../Demonstration_material/SC_2025/SC2025.md): Policy-aware distributed Vertical Federated Learning infrastructure
- [RENCI webinar](../Demonstration_material/RENCI_webinar/RENCI_webinar_25.md): Federated Learning with microservices
- [SuperComputing 2024](../Demonstration_material/SC_2024/SC2024.md): Microservices-based FABRIC implementation of Collaborative Model Training Scenario  with Vertical Federated Learning
- [SuperComputing 2023](../Demonstration_material/SC_2023/SC2023.md): Dynamos: Dynamically Adaptive Microservice-based OS



