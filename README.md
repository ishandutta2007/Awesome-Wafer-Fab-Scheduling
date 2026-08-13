# Awesome-Wafer-Fab-Scheduling

# Top Wafer Fab Scheduling Tools Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Semiconductor Fab Scheduling, Advanced Planning & Scheduling (APS), Dispatching & Manufacturing Execution*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Wafer Fab Scheduling Tools**. These systems handle finite-capacity scheduling, real-time dispatching, WIP tracking, tool utilization optimization, and constraint-based planning across complex semiconductor manufacturing flows (lot, batch, reticle, AMHS, and process constraints).

**Examples** include Applied SmartFactory, Siemens Opcenter APS, Critical Manufacturing, Flexciton, CamLine InFrame Synapse, FactoryLogix, 42Q, Parsec TrakSYS, Asprova APS, and PlanetTogether (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom constraint solvers, reinforcement-learning dispatchers, fab simulators, and open APS engines — ideal for semiconductor manufacturers, researchers, and developers building transparent, adaptable fab scheduling solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Applied SmartFactory](https://www.appliedmaterials.com/)**  
  Industry-leading semiconductor MES and scheduling suite with advanced dispatching, real-time simulation, and unified process control for high-velocity wafer fabs.

- **[Siemens Opcenter APS](https://www.siemens.com/)**  
  Finite-capacity advanced planning and scheduling platform (formerly Preactor) tightly integrated with Siemens MES and manufacturing operations management.

- **[Critical Manufacturing](https://www.criticalmanufacturing.com/)**  
  Modern Industry 4.0 MES with native APS, fabLIVE digital twin, IoT data platform, and flexible scheduling for semiconductor and high-tech manufacturing.

- **[Flexciton](https://www.flexciton.com/)**  
  AI-powered production scheduling and optimization platform focused on complex manufacturing environments including semiconductor and electronics.

- **[CamLine InFrame Synapse](https://www.camline.com/)**  
  Semiconductor-focused MES and factory automation platform providing WIP tracking, dispatching, and advanced process control.

- **[FactoryLogix](https://www.aegissoftware.com/)**  
  Manufacturing execution and operations platform with scheduling, traceability, and shop-floor control suited to electronics and semiconductor assembly.

- **[42Q](https://www.42-q.com/)**  
  Cloud-based MES and manufacturing operations platform offering real-time production visibility, scheduling, and quality management.

- **[Parsec TrakSYS](https://www.parsec-corp.com/)**  
  Manufacturing operations management platform with resource planning, scheduling, dispatching, and production tracking capabilities.

- **[Asprova APS](https://www.asprova.com/)**  
  High-speed finite-capacity scheduling engine designed for complex discrete manufacturing with large numbers of operations and constraints.

- **[PlanetTogether](https://www.planettogether.com/)**  
  Finite-capacity APS with interactive Gantt scheduling, scenario simulation, and strong ERP integration for realistic production plans.

## Open-Source GitHub Projects
- **[frePPLe](https://github.com/frePPLe/frepple)**  
  Leading open-source advanced planning and scheduling (APS) system with finite-capacity planning, multi-level BOMs, material constraints, and REST API integration.

- **[RL4SemiconductorFabSched](https://github.com/ingambe/rl4semiconductorfabsched)**  
  Semiconductor fab scheduling research codebase using self-supervised and reinforcement learning for dispatching policy optimization.

- **[PySCFabSim](https://prosysscience.github.io/PySCFabSim-release/)**  
  High-performance open-source semiconductor fab simulator built for AI dispatching, planning algorithm research, and large-scale experiments.

- **[OpenI40 Platform](https://github.com/openi40/OpenI40Platform)**  
  Open-source advanced production scheduler designed for Industry 4.0 with modular scheduling, MES components, and manufacturing constraints.

- **[OptaPlanner / Timefold Solver](https://github.com/TimefoldAI/timefold-solver)**  
  Powerful open-source constraint solver (successor to OptaPlanner) widely used for job-shop, resource, and complex production scheduling problems.

- **[SAMPO](https://github.com/aimclub/SAMPO)**  
  Open-source framework for adaptive manufacturing process scheduling using meta-heuristics, genetic algorithms, and multi-agent methods.

- **[free-mes](https://github.com/metaxk-company/free-mes)**  
  Open-source Manufacturing Execution System with production scheduling, order management, task dispatching, and real-time dashboards.

- **[qcadoo MES](https://github.com/qcadoo/mes)**  
  Friendly open-source web MES for production management including planning, tracking, and shop-floor control features.

- **[U-APS](https://github.com/iyulab/U-APS-releases)**  
  Hybrid Rust/C# advanced production scheduling system combining optimization algorithms with practical input/output formats.

- **[amhs](https://github.com/david-amirault/amhs)**  
  Simulation and modeling tools for automated material handling systems (AMHS) in modern semiconductor fabs.

### Additional Strong Open-Source Options
- **[ERPNext](https://github.com/frappe/erpnext)** and **[Odoo Community](https://github.com/odoo/odoo)** MRP modules for integrated production planning and basic scheduling.
- Community **job-shop / flexible job-shop solvers**, **genetic programming dispatchers**, and **fab simulation environments**.
- Academic **semiconductor scheduling benchmarks**, **AMHS traffic models**, and **reinforcement-learning fab environments**.
- Many **constraint programming** and **OR-Tools / HiGHS** based custom APS prototypes on GitHub.

**Frameworks for building custom systems**: Combine **frePPLe** or **Timefold Solver** for core scheduling, **PySCFabSim** for high-fidelity fab simulation, **OptaPlanner/Timefold** for constraint modeling, **PostgreSQL + dbt** for manufacturing data, **Grafana** for real-time visibility, and **Ollama** or local LLMs for intelligent dispatch assistants and what-if scenario generation.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Wafer fab scheduling tools must support rigorous process control, traceability, and semiconductor-specific constraints (reticle, batch, AMHS, time links, etc.).
- Self-hosted open-source solutions require proper validation, security, data integrity, and integration testing before production use in a fab environment.

---
**Made for semiconductor manufacturers, fab planners, industrial engineers, researchers, and manufacturing technologists.**
Let's make wafer fab scheduling more open, data-driven, and optimized.
