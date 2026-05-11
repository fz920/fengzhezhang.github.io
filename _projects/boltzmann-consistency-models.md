---
layout: page
title: Efficient Boltzmann Sampling
description: Consistency models with importance sampling for efficient, unbiased Boltzmann distributions.
img: assets/img/projects/mmd-illustrations.png
importance: 1
category: research
related_publications: true
---

This project studies how consistency models can be used as fast proposal samplers for Boltzmann distributions while importance sampling corrects the remaining bias.

The core result is a reduction in function evaluations from 100 to 6-25 while preserving effective sample size on synthetic and equivariant n-body systems.

{% include figure.liquid loading="eager" path="assets/img/projects/mmd-illustrations.png" title="Consistency-model sampling diagnostics" class="img-fluid rounded z-depth-1" %}

Related publication: [Efficient and Unbiased Sampling of Boltzmann Distributions via Consistency Models](/publications/#zhang2024efficient).
