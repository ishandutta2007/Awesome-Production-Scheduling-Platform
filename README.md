# Awesome-Production-Scheduling-Platform

## Top Production Scheduling Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Advanced Planning & Scheduling (APS), Finite Capacity Scheduling, Shop-Floor Sequencing & Manufacturing Optimization*

**Last updated: September 2026**



This repository tracks notable **SaaS/enterprise platforms** and **open-source projects** for **Production Scheduling** (Advanced Planning and Scheduling – APS). These systems generate feasible, optimized production schedules that respect capacity, material, sequencing, and business constraints, often integrated with ERP and MES.



**Examples** include PlanetTogether, Asprova, Preactor APS (Siemens Opcenter APS), FLEXSCHE, DELMIA Ortems, Opcenter APS, Optessa, JustPlanIt, and Quintiq (the category leaders).



**Open-source emphasis**: Full commercial APS platforms dominate complex manufacturing environments. The strongest dedicated open-source option is **frePPLe**. Additional open optimization engines (OptaPlanner, OR-Tools-based projects) and ERP scheduling modules provide building blocks. This section highlights practical open alternatives and is realistic about the gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[PlanetTogether](https://www.planettogether.com/)**  

  Dedicated APS platform for discrete and process manufacturing with strong ERP integration and scenario-based planning.



- **[Asprova](https://www.asprova.com/)**  

  High-speed APS engine widely used in automotive, electronics, and other high-mix manufacturing environments with complex constraints.



- **[Preactor APS / Siemens Opcenter APS](https://www.siemens.com/)**  

  Long-established advanced planning and scheduling solution (now part of Siemens Opcenter) for detailed scheduling and mid-to-long-term planning.



- **[FLEXSCHE](https://www.flexsche.com/)**  

  Flexible production scheduling software focused on detailed shop-floor sequencing and visualization.



- **[DELMIA Ortems](https://www.3ds.com/)**  

  Dassault Systèmes APS solution for production planning and scheduling within the broader DELMIA manufacturing portfolio.



- **[Opcenter APS](https://www.siemens.com/)**  

  Siemens’ current APS offering (evolved from Preactor) integrated into the Opcenter manufacturing operations management suite.



- **[Optessa](https://www.optessa.com/)**  

  Advanced planning and scheduling software using optimization techniques for complex manufacturing environments.



- **[JustPlanIt](https://www.justplanit.com/)** (or similar specialized APS tools)  

  Production planning and scheduling solutions aimed at specific manufacturing needs.



- **[Quintiq (DELMIA Quintiq)](https://www.3ds.com/)**  

  Powerful planning and optimization platform used for complex supply-chain and production scheduling problems.



## Open-Source GitHub Projects

- **[frePPLe](https://github.com/frePPLe/frepple)**  

  Leading open-source advanced planning and scheduling system. Supports finite capacity planning, material constraints, multi-level BOMs, and ERP integration via API.



- **[OptaPlanner](https://github.com/kiegroup/optaplanner)**  

  Open-source constraint satisfaction and optimization engine (Red Hat) that can be used to build custom production scheduling and resource allocation solutions.



- **[OR-Tools and optimization open libraries](https://github.com/google/or-tools)**  

  Google’s open-source optimization suite frequently applied to job-shop, vehicle, and production scheduling problems.



- **[ERPNext and Odoo manufacturing/scheduling modules](https://github.com/frappe/erpnext)**  

  Open-source ERP systems that include production planning, work orders, and basic scheduling capabilities.



- **[Custom APS and job-shop open experiments](https://github.com/)**  

  Research and prototype projects implementing finite scheduling, genetic algorithms, and constraint-based planning for manufacturing.



- **[U-APS and hybrid optimization open releases](https://github.com/)**  

  Emerging open or open-core production scheduling engines combining modern optimization algorithms with practical interfaces.



- **[python-lekin and academic scheduling frameworks](https://github.com/)**  

  Open libraries focused on flexible job-shop and supply-chain scheduling research and prototyping.



- **[Visualization and Gantt open components](https://github.com/)**  

  Open tools for rendering production schedules, resource timelines, and what-if scenarios.



- **[Integration and data-connector open helpers](https://github.com/)**  

  Scripts and connectors for exchanging orders, BOMs, and capacity data between ERPs and scheduling engines.



- **[Constraint modeling open examples](https://github.com/)**  

  Educational repositories demonstrating how to model manufacturing constraints with open solvers.



### Additional Strong Open-Source Options

- Starting with **frePPLe** when a dedicated open-source APS is required.

- Using **OptaPlanner** or **OR-Tools** to build custom scheduling logic for unique constraints.

- Leveraging open ERP manufacturing modules (Odoo, ERPNext) for simpler planning needs.

- Accepting that high-performance finite scheduling, complex multi-constraint optimization at scale, rich scenario management, and deep industry templates still favor commercial APS platforms (PlanetTogether, Asprova, Siemens Opcenter APS, DELMIA, Quintiq, etc.).

- Combining open solvers with commercial or ERP systems for hybrid planning architectures.



**Frameworks for building custom systems**: Model resources, operations, and constraints → feed demand and inventory data from ERP → run frePPLe or a custom OptaPlanner/OR-Tools model → publish schedules back to MES/ERP → iterate with planners. Suitable for manufacturers with technical capacity and well-defined constraints. Commercial APS platforms remain the practical choice for most mid-to-large manufacturers that need proven performance, support, and rapid time-to-value.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Production scheduling systems directly affect manufacturing execution, delivery performance, and costs. Incorrect schedules can cause downtime, shortages, or excess inventory. Open-source or self-built solutions require careful modeling, validation, and ongoing maintenance by qualified personnel. This list is not manufacturing or operational advice.



---

**Made for production planners, manufacturing engineers, and operations leaders who need feasible and optimized schedules.**

Let's keep production planning constraint-aware, agile, and as open as practical.
