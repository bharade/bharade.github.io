---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download PDF version here](/files/Aditya_CV.pdf)

Education
======
*   **M.Tech in Aerospace Engineering** with Specialisation in AI
    *   Indian Institute of Technology Kharagpur (2024 - 2025)
    *   **CGPA:** 8.84/10

*   **B.Tech (Hons.) in Aerospace Engineering** with Specialisation in AI
    *   Indian Institute of Technology Kharagpur (2020 - 2024)
    *   *Dual Degree Program*


Work Experience
======
**IHI Corporation** | *AI Application Analyst (Technology Planning Dept, Corporate R&D)*
*Oct 2025 - Present | Yokohama, Tokyo, Japan*
*   Architected a **techno-economic simulation pipeline** in Python to benchmark SAF pathways, automating sensitivity analysis to identify manufacturing process optimizations yielding a **6.2% cost reduction**.
*   Engineered a **time-series forecasting ensemble** (XGBoost, LightGBM) to model complex $CH_4$ reaction dynamics, achieving **98% prediction accuracy** on 10-minute horizons.
*   Spearheading R&D on **Agentic CAD Workflows** to mitigate spatial hallucinations via structured **Chain-of-Thought** reasoning.

**École Polytechnique Fédérale de Lausanne (EPFL)** | *AI Researcher*
*Apr 2025 - Sept 2025 | Lausanne, Switzerland*
*   *Guide: Prof. Olga Fink (IMOS Lab)*
*   Developed a novel physics-informed **Graph Neural Network** pipeline for **fault localisation** using temporal Lamb waves.
*   Processed **71,000+ time-series entries** and constructed fully connected graphs using **PyTorch Geometric**.
*   **Enhanced generalisation by 35%** on unseen faults through a novel **attention-based spectral grid localiser**.
*   Implemented **DeepMind's SOTA Graph Network Simulator**, performing temporal rollout for increased adaptability.

**IHI Corporation** | *AI R&D Intern*
*May 2024 - July 2024 | Tokyo, Japan*
*   Demonstrated a **20% carrying cost reduction** and **50% stockouts reduction** using CNNs for inventory management.
*   Implemented a predictive maintenance tool using **XGBoost, LSTM and Autoencoders**, achieving a 0.89 F1-score.
*   Developed a strategic roadmap for IT and business integration for the hybrid aircraft program.

**CSIR-National Aerospace Laboratories** | *Research Intern*
*May 2023 - June 2023 | Bengaluru, India*
*   Deployed Stanford University's **SU2 solver (C++)** to study pressure fluctuations over launch vehicles.
*   Investigated transonic flow behavior, validating wind tunnel results with numerical computations (31.2% increase in pressure coefficient observed).

Skills
======
*   **Core AI:** Graph Neural Networks (GNNs), JAX, Flax, PyTorch Geometric, Transformers, Time-Series Forecasting
*   **Engineering:** Docker, AWS (Machine Learning Specialty), CI/CD, Git
*   **Physics:** Computational Fluid Dynamics (CFD), SU2, Aeroelasticity
*   **Languages:** Python, C++, MATLAB

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>