---
title: "Diversity Decay: Gaussian Simulation"
collection: portfolio
excerpt: 'Monte Carlo simulation of diversity decay in a 1-D Gaussian model retrained on its own samples. Code for [Modeling Diversity Decay in Synthetic Retraining](/publication/2026-diversity-decay).'
---

[GitHub repository](https://github.com/juholee10/gaussian-toy-model) · Paper: [Modeling Diversity Decay in Synthetic Retraining](/publication/2026-diversity-decay)

Code for the Gaussian setting of the paper. Each generation refits a 1-D Gaussian to samples drawn from the previous generation's fit, over 500 independent trials. The simulations compare three settings: no filtering, a fixed-radius verifier, and the verifier with 10% fresh real data each generation.

The CVAE/MNIST experiments are in a separate project: [Diversity Decay: CVAE/MNIST Experiments](/portfolio/diversity-decay-synthetic-retraining/).
