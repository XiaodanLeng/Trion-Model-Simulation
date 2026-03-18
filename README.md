# The Trion Model: A Bottom-Up Simulation of Cortical Function

## Overview
This repository houses the modern Python/NumPy implementation of the **Trion Model**, a foundational neuronal theory of higher brain function originally developed by Dr. Xiaodan Leng and Dr. Gordon Shaw at the University of California, Irvine. 

Unlike top-down artificial neural networks trained on massive datasets, the Trion Model represents a "bottom-up" philosophy of brain emulation. It simulates cortical mini-columns (Trions) utilizing biologically plausible structures to demonstrate how complex, emergent spatio-temporal behaviors arise organically from simulated neural architectures.

## Historical Context & Foundational Papers
This computational project digitizes and scales the mathematical models originally published in the late 1980s and early 1990s:
1. *Towards a neuronal theory of higher brain function using music as a window* (Concepts of Neuroscience, 1991)
2. *Coding of Music Structures and the Trion mode of the cortex* (Music Perception, 1990)
3. *Model of the adaptive temporal development of finite systems* (Physical Review A, 1989)

## Mathematical & Biological Architecture
The simulation is built upon three core pillars:
* **The Trion Unit:** Representing a highly interconnected group of ~100 neurons, operating in discrete time steps with three levels of firing activity (below-average, average, above-average).
* **Static Inherited Connections (Kac-Moody Algebra):** The underlying, fixed geometric structure of the cortical connections, mathematically derived from Kac-Moody algebra to satisfy sum-to-zero constraints.
* **Dynamic Plasticity (Hebbian Learning):** A dynamic connection matrix that updates at each time step based on Hebbian learning rules and a two-time-step memory, subject to synaptic fluctuation.

## Current Project Roadmap (Active Development - 2026)
This project is currently under active development, translating the original 1989 algorithms into a modern, high-performance scientific computing environment.

- [x] **Phase 0:** Architectural Blueprinting and Mathematical Extraction.
- [ ] **Phase 1:** Core Engine Implementation (Python, NumPy) for Monte Carlo simulation loops.
- [ ] **Phase 2:** Spatio-temporal pattern validation and visualization (Matplotlib).
- [ ] **Phase 3:** Exploring compute scaling and dynamic parameter tuning.

*Author: Dr. Xiaodan Leng*  
*Contact: Xiaodan.Leng.Neuro@gmail.com*
