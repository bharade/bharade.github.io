g **DeepMind's Graph Network Simulator** for damage localization in composites.<br/><img src='/images/epfl_gnn.png'>"
collection: portfolio
---

**Role:** AI Researcher | EPFL (Lausanne, Switzerland)
**Lab:** Intelligent Maintenance and Operating Systems (Prof. Olga Fink)
**Stack:** PyTorch Geometric, Spectral GNNs, DeepMind Graph Nets

## Overview
Traditional structural health monitoring relies on manual feature engineering. I developed a **Graph Neural Network (GNN)** pipeline that treats sensor networks as a graph topology to localize impact damage in aircraft composites using Lamb Waves.

## Key Technical Contributions
*   **Graph Construction:** Processed **71,000+ time-series entries** and constructed fully connected graphs using **PyTorch Geometric**.
*   **Physics-Informed Architecture:** Implemented **DeepMind’s SOTA Graph Network Simulator**, performing temporal rollouts to model wave propagation physics.
*   **Novel Attention Mechanism:** Enhanced generalization by **35% on unseen faults** through a novel **attention-based spectral grid localizer**.
*   **Benchmarking:** Achieved an additional **5% generalization benefit** by benchmarking the coupled model against traditional ML baselines.