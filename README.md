# Chaos-To-Crystal
Python implementations of the Pennes Bioheat Equation to model neural entropy reduction and the thermodynamic signature of insight.
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18154048.svg)](https://doi.org/10.5281/zenodo.18154048)
Chaos to Crystal: The Physics of Realization

This repository contains the source code and simulation scripts for the research paper "From Chaos to Crystal," which models cognitive "insight" as a thermodynamic phase transition.

The core hypothesis posits that the brain operates in two energetic regimes:
* Static Maintenance: Sustaining coherent thought patterns against entropic decay.
* Transient Evolution: The collapse of stochastic neural noise into crystallized understanding.
Using Finite Element Analysis (FEA), this codebase proves that the "crystallization" of a thought releases a distinct burst of metabolic energy.

The Simulations:
This repository includes three validated computational models:
Sim 1: Solves the Poisson equation to quantify the metabolic load of sustained focus. Validates the formation of a "Hot Core" (T_max approx. 22.69).
Sim 2: Solves the Heat Diffusion equation to track the collapse of a high-energy "flash" event into equilibrium.
Sim 3: (The Master Simulation) Implements the Pennes Bioheat Equation on a spherical manifold. It accounts for tissue conduction, metabolic generation (Q_met), and blood perfusion sinks to replicate the biological "Heat Flash" of approx. 0.029℃.

Tech Stack:
Solver: scikit-fem (Finite Element Method)
Visualization: PyVista (3D Thermal Gradient Rendering)
Math: NumPy / SciPy

Usage:
Run the transient simulation to visualize the thermodynamic signature of an idea
