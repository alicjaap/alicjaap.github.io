---
title: "Accelerated Bayesian parameter estimation and model selection for gravitational waves with normalizing flows"
collection: publications
permalink: /publication/2024-neurips
excerpt:
date: 2024-10-28
venue: 'Machine Learning and the Physical Sciences Workshop, NeurIPS 2024'
paperurl: 'https://arxiv.org/abs/2410.21076'
---

We present an accelerated pipeline, based on high-performance computing techniques and normalizing flows, for joint Bayesian parameter estimation and model selection and demonstrate its efficiency in gravitational wave astrophysics. We integrate the Jim inference toolkit, a normalizing flow-enhanced Markov chain Monte Carlo (MCMC) sampler, with the learned harmonic mean estimator. Our Bayesian evidence estimates run on 1 GPU are consistent with traditional nested sampling techniques run on 16 CPU cores, while reducing the computation time by factors of 5× and 15× for 4-dimensional and 11-dimensional gravitational wave inference problems, respectively. Our code is available in well-tested and thoroughly documented open-source packages, ensuring accessibility and reproducibility for the wider research community.


[Download paper here](https://arxiv.org/pdf/2410.21076)