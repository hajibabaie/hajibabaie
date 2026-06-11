<picture>
  <source media="(prefers-color-scheme: dark)" srcset="banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="banner-light.svg">
  <img alt="Mohammad Hajibabaie — Operations Research · Combinatorial Optimization · Python" src="banner-light.svg" width="100%">
</picture>

PhD candidate at TU Clausthal, finishing a dissertation on the **Vehicle Platooning Problem**: coordinating truck routes and schedules so vehicles form fuel-saving convoys on real road networks. I work on both sides of the methodology — exact optimization (MILP with Gurobi) and metaheuristics — and benchmark them against each other at scale. Seven years of university teaching and thesis supervision alongside the research.

What I care about: clean mathematical models, reproducible experiments, and code that separates the problem from the algorithm.

## Methods

- **Exact optimization** — MILP modeling, Benders decomposition, two-stage stochastic programming (SAA), chance constraints · Gurobi, CPLEX, HiGHS, SCIP
- **Metaheuristics** — GA, SA, PSO, ACO, CMA-ES; multi-objective: NSGA-II, MOPSO, SPEA2, PESA-II, MOEA/D — built as reusable, problem-agnostic engines
- **ML × OR** — deep learning foundations (DeepLearning.AI specialization); currently building LLM-assisted optimization workflows

## Selected repositories

| Repository | Summary |
|---|---|
| [multi-objective-vehicle-platooning-problem](https://github.com/hajibabaie/multi-objective-vehicle-platooning-problem) | Joint route and speed selection for truck platooning — six multi-objective metaheuristics benchmarked against the exact Pareto front of a MILP solved with Gurobi. The core problem of my PhD. |
| [multi-objective-scheduling](https://github.com/hajibabaie/multi-objective-scheduling) | Energy-aware tri-objective flow-shop & job-shop scheduling (makespan, tardiness, energy) on the Taillard benchmarks — NSGA-II, MOEA/D, and MOPSO from scratch with adaptive operator selection, Dockerized PostgreSQL experiment tracking, and a full nonparametric statistical comparison. |
| [stochastic-facility-location](https://github.com/hajibabaie/stochastic-facility-location) | Two-stage stochastic capacitated facility location with SAA, a service-level chance constraint, and Benders decomposition. Solver-agnostic backends (HiGHS / SCIP / Gurobi). |
| [multi-objective-optimization](https://github.com/hajibabaie/multi-objective-optimization) | NSGA-II, MOPSO, SPEA2, PESA-II, and MOEA/D implemented from scratch and compared on benchmark problems. |
| [genetic-algorithm](https://github.com/hajibabaie/genetic-algorithm) | Problem-agnostic GA engine with pluggable encodings (binary, real, permutation, mixed), applied to classic OR problems. |
| [ant-colony-optimization](https://github.com/hajibabaie/ant-colony-optimization) | ACO for discrete and continuous optimization on a shared metaheuristic core. |

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Gurobi](https://img.shields.io/badge/Gurobi-DD2113?style=flat-square)
![CPLEX](https://img.shields.io/badge/CPLEX-0F62FE?style=flat-square)
![HiGHS](https://img.shields.io/badge/HiGHS-6E40C9?style=flat-square)
![SCIP](https://img.shields.io/badge/SCIP-0E7490?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-018BFF?style=flat-square&logo=neo4j&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-2D333B?style=flat-square&logo=linux&logoColor=white)

## Contact

[LinkedIn](https://www.linkedin.com/in/mo-hajibabaie) · Germany · Open to OR Scientist / Applied Scientist roles
