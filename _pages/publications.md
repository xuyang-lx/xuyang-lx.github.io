---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=RwBW8jUAAAAJ)

---
## [Mechanics-Informed Autoencoder Enables Automated Detection and Localization of Unforeseen Structural Damage](https://www.nature.com/articles/s41467-024-52501-4)
Nature Communications 2024 [[GitHub]](https://github.com/human-analysis/midas-shm) [[Editors' Highlights]](https://www.nature.com/collections/fhffefjdca#:~:text=Mechanics%2Dinformed%20autoencoder%20enables%20automated%20detection%20and%20localization%20of%20unforeseen%20structural%20damage)

<figure>
  <img src="/files/publications/MIDAS.png" alt="Description of the image" style="width: 800px;" />
  <figcaption><strong>MIDAS framework for automated detection and localization of unforeseen structural damage</strong>. MIDAS is a synergistic integration of entirely passive measurements from inexpensive sensors, data compression, and a mechanics-informed autoencoder.</figcaption>
</figure>

---
# [Estimating field parameters from multiphysics governing equations with scarce data](https://openreview.net/pdf?id=IofxiPg6uE)
ICLR Workshop on AI4DifferentialEquations In Science 2024

---
## ParaFIND: Parameter Field Inference on Non-uniform Domains using Neural Network
NeurIPS Workshop on Data-driven and Differentiable Simulations, Surrogates, and Solvers. 2024

---
## [Data-driven mechanical behavior modeling of granular biomass materials](https://doi.org/10.1016/j.compgeo.2024.106907)
Computers and Geotechnics 2024

---
## [NeuralSI: Structural Parameter Identification in Nonlinear Dynamical Systems](https://link.springer.com/chapter/10.1007/978-3-031-25082-8_22)
ECCV European Conference on Computer Vision Workshops 2022 [[GitHub]](https://github.com/human-analysis/neural-structural-identification)

<figure>
  <img src="/files/publications/NeuralSI.png" alt="Description of the image" style="width: 700px;" />
  <figcaption><strong>NeuralSI framework</strong>. We propose NeuralSI for nonlinear dynamic system identification that allows us to discover the unknown parameters of partial differential equations from measured sensing data.</figcaption>
</figure>

---
## [Methods for the rapid detection of boundary condition variations in structural systems](https://asmedigitalcollection.asme.org/SMASIS/proceedings-abstract/SMASIS2022/86274/1150809)
Smart Materials, Adaptive Structures and Intelligent Systems (SMASIS) 2022

---
## [Physics informed neural network for dynamic stress prediction](https://link.springer.com/article/10.1007/s10489-023-04923-8)
Applied Intelligence 2023

---
## [Neuro-DynaStress: Predicting Dynamic Stress Distributions in Structural Components](https://arxiv.org/pdf/2301.02580)
arXiv preprint 2022

---
## [Deep learning paradigm for prediction of stress distribution in damaged structural components with stress concentrations](https://www.sciencedirect.com/science/article/abs/pii/S0965997822001430)
Advances in Engineering Software 2022

---
## [Bridging finite element and deep learning: High-resolution stress distribution prediction in structural components](https://link.springer.com/article/10.1007/s11709-022-0882-5)
Frontiers of Structural and Civil Engineering 2022

---
## [Functionally graded materials beams subjected to bilateral constraints: Structural instability and material topology](https://www.sciencedirect.com/science/article/pii/S002074032034323X)
International Journal of Mechanical Sciences 2021

---
## [Postbuckling of multi-direction anisotropic constrained functionally graded material beams](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11589/115890G/Postbuckling-of-multi-direction-anisotropic-constrained-functionally-graded-material-beams/10.1117/12.2593628.short)
Behavior and Mechanics of Multifunctional Materials 2021
