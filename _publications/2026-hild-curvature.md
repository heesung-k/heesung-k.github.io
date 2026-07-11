---
title: "A Simple and Efficient Measure of Loss Landscape Curvature"
collection: publications
permalink: /publication/2026-hild-curvature
category: ml
excerpt: 'A scalable directional-curvature measure and forward-pass estimators for tracking Edge-of-Stability dynamics without Hessian-vector products.'
date: 2026-07-10
venue: 'ICML Workshop on High-dimensional Learning Dynamics (HiLD)'
publication_type: workshop
authors: '**Hee-Sung Kim**, Sungyoon Lee'
paperurl: 'https://openreview.net/pdf?id=PnHMyT7qP2'
posterurl: '/files/SCM_Poster.pdf'
citation: |-
  @inproceedings{
  kim2026simple,
  title={A Simple and Efficient Measure of Loss Landscape Curvature},
  author={Hee-Sung Kim and Sungyoon Lee},
  booktitle={High-dimensional Learning Dynamics 2026},
  year={2026},
  url={https://openreview.net/forum?id=PnHMyT7qP2}
  }
---

**Authors:** **Hee-Sung Kim**, Sungyoon Lee

**Venue:** High-dimensional Learning Dynamics (HiLD), ICML 2026 Workshop

We revisit a scalable measure of loss-landscape curvature along the optimizer's update direction. Its one-step descent boundary remains at $\(2/\eta\)$ across optimizers, including momentum and adaptive methods. We also propose finite-difference and KL-divergence estimators that reproduce Edge-of-Stability dynamics using only one or two additional forward passes per step, without Hessian-vector products.
