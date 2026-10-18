---
title: "Modeling Diversity Decay in Synthetic Retraining"
collection: publications
category: manuscripts
permalink: /publication/2026-diversity-decay
date: 2026-09-01
venue: 'Under review in the <a href="https://journaljyi.org">Journal of Youth Impact</a>'
excerpt: 'Modeling diversity decay when AI models recursively train on self-generated data.<br />Download: [PDF (LaTeX version)](/files/DiversityDecayTex.pdf) · [PDF (Word version)](/files/DiversityDecayWord.pdf)<br />Code: [Gaussian simulation](/portfolio/gaussian-toy-model/) · [CVAE/MNIST experiments](/portfolio/diversity-decay-synthetic-retraining/)'
---

When generative models are retrained on their own synthetic data, the diversity of their outputs can decay over generations, a problem known as model collapse. This paper studies that decay in two settings. First, a Gaussian model gives a proof of diversity loss, supported by simulation. Second, a CVAE trained on MNIST compares three retraining strategies: no filtering, verifier filtering, and verifier filtering combined with real data. The main finding is that common metrics can miss or misrepresent diversity loss.

Written through the Seoul Research Program, mentored by Professor Haifeng Xu (University of Chicago).

Download: [PDF (LaTeX version)](/files/DiversityDecayTex.pdf) · [PDF (Word version)](/files/DiversityDecayWord.pdf)

Code: [Gaussian simulation](/portfolio/gaussian-toy-model/) · [CVAE/MNIST experiments](/portfolio/diversity-decay-synthetic-retraining/)
