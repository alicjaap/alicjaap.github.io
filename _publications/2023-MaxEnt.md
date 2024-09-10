---
title: "Learned harmonic mean estimation of the marginal likelihood with normalizing flows"
collection: conference
permalink: /publication/2023-MaxEnt
excerpt:
date: 2023-06-30
venue: 'Presented at the 42nd International Workshop on Bayesian Inference and Maximum Entropy Methods in
Science and Engineering, Garching, Germany, 3–7 July 2023'
paperurl: 'https://arxiv.org/abs/2307.00048'
---

Computing the marginal likelihood (also called the Bayesian model evidence) is an important task in Bayesian model selection, providing a principled quantitative way to compare models. The learned harmonic mean estimator solves the exploding variance problem of the original harmonic mean estimation of the marginal likelihood. The learned harmonic mean estimator learns an importance sampling target distribution that approximates the optimal distribution. While the approximation need not be highly accurate, it is critical that the probability mass of the learned distribution is contained within the posterior in order to avoid the exploding variance problem. In previous work a bespoke optimization problem is introduced when training models in order to ensure this property is satisfied. In the current article we introduce the use of normalizing flows to represent the importance sampling target distribution. A flow-based model is trained on samples from the posterior by maximum likelihood estimation. Then, the probability density of the flow is concentrated by lowering the variance of the base distribution, i.e. by lowering its "temperature", ensuring its probability mass is contained within the posterior. This approach avoids the need for a bespoke optimisation problem and careful fine tuning of parameters, resulting in a more robust method. Moreover, the use of normalizing flows has the potential to scale to high dimensional settings. We present preliminary experiments demonstrating the effectiveness of the use of flows for the learned harmonic mean estimator. The harmonic code implementing the learned harmonic mean, which is publicly available, has been updated to now support normalizing flows.

[Download paper here](https://arxiv.org/pdf/2307.00048.pdf)