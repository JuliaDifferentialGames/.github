# JuliaDifferentialGames

**Open-source tools for Differential Games and Multi-Agent Control in Julia**

The **JuliaDifferentialGames** organization builds a high-performance, research-grade ecosystem for modeling, solving, and learning **differential games** and **multi-agent dynamical systems**. Our libraries integrate modern numerical optimal control, dynamic programming, kinodynamic motion planning, and inverse problem methods to support advanced research and real-world applications.

This organization is under active development, with several core packages already available and additional libraries in progress.

---

## Current Libraries 

> ⚠️ **Work in progress**
>
> These libraries are currently under active development and not all capabilites have been released yet, but will (hopefully) be soon.



### DifferentialGames.jl
**Core library for differential game modeling and solution methods.**

Key capabilities:
- Continuous and discrete-time differential games  
- Zero-sum, general-sum, and cooperative formulations
- Support for Multi-agent Reinforcement Learning (MARL) algorithms
- Open-loop and feedback Nash equilibria  
- Customizable dynamics, costs, and constraints  
- Interoperable with Julia’s scientific computing ecosystem  

This package serves as the foundation for multi-agent optimal control and game-theoretic analysis in Julia.

---

### DynamicPlanning.jl
**Kinodynamic motion planning for warm-starting differential games.**

Designed for dynamic and high-dimensional systems:
- Kinodynamic planning (RRT, RRT*, variants)  
- Planning-to-optimization workflows  
- Warm-start generation for multi-agent game solvers  
- Tools for global strategy initialization  

Ideal for initializing complex trajectories before game-theoretic refinement.

---

### IterativeRegularization.jl
**Solvers for nonlinear inverse problems**

Provides advanced iterative methods:
- Landweber Method
- Iteratively Regularized Gauss–Newton (IRGN)  
- Nonlinear multigrid regularization  

This package is a general package for numerical analysis of inverse problems.

---

## Planned Libraries

### AmortizedOptimization.jl
**Learning-based optimization and amortized solvers.**

Planned features:
- Neural warm-starts for repeated game solves  
- Differentiable optimization layers  
- Meta-learning for value functions and costates  
- Integration with Flux, Zygote, and scientific machine learning ecosystems  

Targeted toward differential games and optimal control.

---

### CBFs.jl
**Control Barrier Functions integrated directly into optimization problems.**

Focus areas:
- Optimization-native CBF formulations  
- Multi-agent safety constraints embedded in game objectives  
- Scalable feasibility and safety enforcement  
- Differentiable CBF integration for closed-loop control  

This package will support rigorous safety-critical control in multi-agent settings.

---

## Mission and Scope

JuliaDifferentialGames aims to provide a unified, composable environment for:

- **Differential games and multi-agent optimal control**  
- **Dynamic programming and motion planning**  
- **Inverse differential games**  
- **Learning-enhanced optimization methods**  
- **Safety-critical control and control barrier function design**

By building on Julia’s strengths in scientific computing, we seek to deliver tools that are fast, expressive, and suitable for cutting-edge research in robotics, aerospace, autonomous systems, and computational game theory.

---

## Contributing

We welcome contributions from the community. Early involvement is especially valuable as interfaces evolve.

Ways to contribute:
- Propose features or improvements through GitHub Issues  
- Participate in API design discussions  
- Contribute solvers, benchmarks, or documentation  
- Share example notebooks or case studies  

A full CONTRIBUTING guide will be added as the ecosystem matures.

---

## License

Packages within this organization are generally released under the **MIT License** unless otherwise specified.

---

## Project Status

The ecosystem is **actively expanding**. APIs and interfaces may change as new solvers and workflows are integrated. For research or production use, we recommend pinning versions and tracking release notes.
- a visual diagram of the ecosystem  
- a project logo in SVG format  
