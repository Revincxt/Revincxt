<div align="center">

<h1>Revincxt</h1>

<h3>Planning, learning, and reproducible autonomous systems.</h3>

<p>
I build research-oriented software for decision-making under spatial, temporal, and resource constraints.
</p>

<p>
<code>automated planning</code>&nbsp;&nbsp;
<code>reinforcement learning</code>&nbsp;&nbsp;
<code>scheduling</code>&nbsp;&nbsp;
<code>simulation</code>
</p>

<p>
<a href="#selected-systems">Selected systems</a>
&nbsp;·&nbsp;
<a href="#research-approach">Research approach</a>
&nbsp;·&nbsp;
<a href="https://github.com/Revincxt?tab=repositories">All repositories</a>
</p>

</div>

---

## About

My work connects **automated planning**, **reinforcement learning**, and **simulation** to study how autonomous systems make decisions under real constraints. I prefer small, inspectable systems with explicit assumptions, reproducible experiments, and evidence that can be audited beyond a final score.

> 我关注规划、学习与自主系统，并把研究问题做成可验证、可复现的工程实验。

## Research focus

- **Planning and search** — graph search, any-angle planning, incremental replanning, and space–time reasoning.
- **Learning and adaptation** — reinforcement learning and hybrid agents that remain measurable and inspectable.
- **Scheduling and autonomy** — decision-making under visibility, geometry, energy, storage, timing, and safety constraints.

## Selected systems

### [UAV 3D Planner Lab](https://github.com/Revincxt/uav-3d-planner)

`3D path planning` `dynamic replanning` `predictive 4D planning`

A reproducible study of static 3D planning, dynamic replanning, and predictive space–time planning in structured urban airspace. It separates planner output, geometry processing, execution qualification, and collision auditing so that algorithm comparisons remain traceable.

**Methods:** 3D A*, Lazy Theta*, RRT*, D* Lite, and 4D Space-Time A*

**Explore:** [Live study](https://revincxt.github.io/uav-3d-planner/predictive.html) · [Methodology](https://github.com/Revincxt/uav-3d-planner/blob/main/docs/methodology.md) · [Releases](https://github.com/Revincxt/uav-3d-planner/releases)

### [OrbitOps Lab](https://github.com/Revincxt/orbitops-lab)

`earth-observation scheduling` `optimization` `reproducible experiments`

A research framework for constrained Earth-observation scheduling. Baseline, exact, stochastic-search, and learning-based solvers share a common simulator and independent validation path across visibility, overlap, slew, energy, and storage constraints.

**Evidence:** schedules, resource envelopes, convergence traces, and auditable run artifacts

**Explore:** [Research interface](https://revincxt.github.io/orbitops-lab/) · [Problem formulation](https://github.com/Revincxt/orbitops-lab/blob/main/docs/problem-formulation.md) · [Benchmarking](https://github.com/Revincxt/orbitops-lab/blob/main/docs/benchmarking.md)

### [Adaptive Agent Lab](https://github.com/Revincxt/adaptive-agent)

`planning` `reinforcement learning` `hybrid agents` `alpha`

An alpha-stage laboratory for comparing planning, replanning, tabular learning, Dyna-Q, DQN, and option-based hybrid agents in dynamic single-robot warehouse delivery.

**Status:** browser demonstrations are explicitly separated from confirmatory evidence

**Explore:** [Replay explorer](https://revincxt.github.io/adaptive-agent/) · [Problem formulation](https://github.com/Revincxt/adaptive-agent/blob/main/docs/problem-formulation.md) · [Experiment protocol](https://github.com/Revincxt/adaptive-agent/blob/main/docs/experiment-protocol.md)

## Earlier planning work

- [satellitesMissionSchedule](https://github.com/Revincxt/satellitesMissionSchedule) — reinforcement-learning experiments for agile satellite mission scheduling.
- [GTPyhop](https://github.com/Revincxt/GTPyhop) — a Python Goal-Task Network planning system for constructing plans from tasks and goals.

## Research approach

`problem formulation → algorithms → simulation → validation → evidence`

- Define the model scope, assumptions, and non-goals explicitly.
- Separate algorithms from simulation, validation, and presentation.
- Version seeds, configurations, schemas, and experimental artifacts.
- Report limitations and failure evidence, not only the best score.

## Current direction

I am exploring how planning and learning can work together without losing inspectability: systems that adapt, expose why they fail, and support reproducible evaluation.

---

<div align="center">

<sub>Research software for planning, learning, scheduling, and autonomous decision-making.</sub>

</div>
