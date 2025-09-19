---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

> **Research Focus**: Probabilistic Generative Models | Computational Chemistry | Scientific Machine Learning

Education
======
* **MPhil Machine Learning and Machine Intelligence** | *University of Cambridge* (2023-2024)
  * **Distinction** with score of 79.87%, ranking in the **top 10%** of cohort
  * **Supervisor**: Prof. José Miguel Hernández-Lobato
  * **Dissertation**: "Sampling of Molecular Energy Functions via Consistency Models" (Distinction)
  * **Relevant Coursework**: Advanced Machine Learning, Probabilistic Machine Learning, Deep Learning, Reinforcement Learning

* **BSc Mathematics** | *Imperial College London* (2020-2023)
  * **First Class Honours** with score of 88.41%, ranking **10th out of 251 students** (top 4%)  
  * **Relevant Coursework**: Probability & Statistics, Numerical Analysis, Optimization, Mathematical Biology, Computational Methods

Research Experience
======

**Research Assistant** | *University of Cambridge* (October 2024 – Present)
* **Supervisor**: Prof. José Miguel Hernández-Lobato  
* **Project**: Variance-Tuned Diffusion Models for Boltzmann Sampling
* Developing novel deep generative models (diffusion models, normalizing flows) for molecular generation
* Focus on theoretical guarantees for unbiased sampling with computational efficiency improvements
* Applications in drug discovery and materials science through accelerated molecular dynamics

**MPhil Dissertation Researcher** | *University of Cambridge* (April 2024 – August 2024)
* **Supervisor**: Prof. José Miguel Hernández-Lobato
* **Title**: "Sampling of Molecular Energy Functions via Consistency Models"
* **Achievement**: Dissertation awarded **Distinction**
* Created novel Consistency-Model + importance-sampling framework yielding **≈4× speedup** over DDPM baselines
* Developed unbiased estimators for molecular energy functions with theoretical convergence guarantees
* Implemented and benchmarked algorithms on real molecular datasets

**Undergraduate Research Assistant** | *Imperial College London* (July 2023 – October 2023)  
* **Supervisor**: Dr. Yingzhen Li
* **Project**: Adaptive KL Regularization for Variational Autoencoders
* Proposed novel algorithm for direct KL divergence regulation during VAE training
* Eliminated need for β-VAE hyperparameter sweeps across multiple architectures
* Demonstrated improved training stability and representation quality

**Undergraduate Group Project Leader** | *Imperial College London* (May 2022 - June 2022)
* **Supervisor**: Dr. Sheehan Olver  
* **Achievement**: Winner of **The Winton Prize** for best Mathematics group project
* Developed deflation-based method for discovering multiple solutions of nonlinear ODE/PDE systems
* Implemented robust numerical algorithms with single initial guess requirement

Teaching Experience
======
* **Peer Tutor and Teaching Assistant**, Imperial College London (October 2022 – April 2023)
  * Led group tutorials for first-year students, covering Probability, Analysis, and Calculus, with a focus on advanced mathematical problem-solving to enhance academic understanding and performance
  * Provided support for second-year students in the Numerical Analysis module, offering guidance in Julia programming and fostering a deeper understanding of computational methods

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Technical Skills
======

**Programming Languages**
* **Python** (Expert): PyTorch, TensorFlow, JAX, NumPy, SciPy, scikit-learn
* **Julia** (Proficient): DifferentialEquations.jl, Flux.jl, Plots.jl
* **MATLAB** (Proficient): Optimization, numerical computing, visualization
* **R** (Intermediate): Statistical analysis and modeling

**Machine Learning Frameworks**
* **Deep Learning**: PyTorch Lightning, Weights & Biases, Hydra
* **Probabilistic Modeling**: Pyro, Edward, TensorFlow Probability  
* **Scientific Computing**: JAX, AutoDiff, parallel computing

**Research Tools**
* **Molecular Simulation**: OpenMM, RDKit, molecular dynamics
* **Computational Chemistry**: Quantum chemistry packages, energy function optimization
* **High-Performance Computing**: SLURM, distributed training, GPU computing

**Software Development**
* **Version Control**: Git, GitHub, collaborative development
* **Documentation**: LaTeX, Jupyter notebooks, technical writing
* **Deployment**: Docker, cloud computing (AWS, Google Cloud)

Scholarships & Awards  
======
* **The Winton Prize** – Outstanding undergraduate group project in Mathematics (2022)
* **Dean's List** – Recognized among top 10% of students (2021, 2022, 2023)  
* **Undergraduate Research Bursary** – Awarded by Mathematics Department (2022)
* **MPhil Distinction** – Top 10% performance in Machine Learning program (2024)
