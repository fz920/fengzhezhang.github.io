---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **MPhil Machine Learning and Machine Intelligence**, University of Cambridge, Cambridge, UK (October 2023 - September 2024)
  * Achieved a score of 79.87% (Distinction), ranking in the top 10%

* **BSc Mathematics**, Imperial College London, London, UK (October 2020 - June 2023)
  * Achieved a score of 88.41% (First Class Honours), ranking in the top 4% (10th out of 251 students)

Research Experience
======
* **Research Assistant**, University of Cambridge (October 2024 – October 2025, expected)
  * Supervisor: Prof. José Miguel Hernández-Lobato
  * Developing and applying deep generative models—such as diffusion models and normalizing flows—to accelerate molecular generation and improve sampling accuracy

* **MPhil Dissertation**, University of Cambridge (April 2024 – August 2024)
  * Supervisor: Prof. José Miguel Hernández-Lobato
  * Created a Consistency-Model + importance-sampling framework that yields unbiased samples from molecular energy functions and being ≈4×faster than DDPM baselines; dissertation awarded Distinction

* **Undergraduate Research Assistant**, Imperial College London (July 2023 – October 2023)
  * Supervisor: Dr Yingzhen Li
  * Proposed and experimented a novel algorithm to directly regulate KL divergence during VAE training, eliminating β-VAE hyper-parameter sweeps and generalising to multiple VAE architectures

* **Undergraduate Group Project**, Imperial College London (May 2022 - June 2022)
  * Supervisor: Dr Sheehan Olver
  * Developed a deflation-based method to uncover multiple solutions of nonlinear ODE/PDE systems from a single initial guess; project won the Winton Prize for best Mathematics group project

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
  
Scholarships & Awards
======
* **Dean's List** - Recognized among the top 10% of students (2021, 2022, 2023)
* **Undergraduate Research Bursary** - Awarded by the Mathematics Department (2022)
* **The Winton Prize** – Outstanding undergraduate 2nd-year group project prize in Mathematics (2022)
