---
title: "Modeling Diversity Decay in Synthetic Retraining"
collection: publications
category: preprints
permalink: /publication/2026-diversity-decay
date: 2026-09-01
venue: 'Under review'
paperurl: # TODO(juho): arXiv or PDF link (if you add files/diversity-decay.pdf, use /files/diversity-decay.pdf)
excerpt: 'How diversity is lost when models retrain on their own synthetic data, and why common metrics can miss it.'
---

When generative models are retrained on their own synthetic data, the diversity of their outputs can decay over generations, a problem known as model collapse. This paper studies that decay in two settings. First, a Gaussian model gives a proof of diversity loss, supported by simulation. Second, a CVAE trained on MNIST compares three retraining strategies: no filtering, verifier filtering, and verifier filtering combined with real data. The main finding is that common metrics can miss or misrepresent diversity loss.

Written through the Seoul Research Program, mentored by Professor Haifeng Xu (University of Chicago).
