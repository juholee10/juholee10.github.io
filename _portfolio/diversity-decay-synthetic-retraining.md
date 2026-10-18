---
title: "Diversity Decay: CVAE/MNIST Experiments"
collection: portfolio
excerpt: 'Recursive retraining of a conditional VAE on its own MNIST samples, with and without a verifier. Code for [Modeling Diversity Decay in Synthetic Retraining](/publication/2026-diversity-decay).'
---

[GitHub repository](https://github.com/juholee10/diversity-decay-synthetic-retraining) · Paper: [Modeling Diversity Decay in Synthetic Retraining](/publication/2026-diversity-decay)

Code for the CVAE/MNIST experiments of the paper. A CVAE trained on 500 real MNIST digits is retrained from scratch on its own samples for 50 generations under three conditions: no verifier, a discriminator that keeps the top 10% of samples, and the discriminator plus 10% real data. Each generation is measured with the Vendi Score, Coverage, FID, and held-out reconstruction loss.

The Gaussian simulation is in a separate project: [Diversity Decay: Gaussian Simulation](/portfolio/gaussian-toy-model/).
