---
layout: page
title: Differential Privacy in Deep Learning
description: Evaluating privacy-performance trade-offs using the PATE framework.
importance: 4
category: Data Science
---

A research-focused study on maintaining data privacy without sacrificing model utility. This project explored formal privacy guarantees when training deep learning models on sensitive financial datasets.

### Technical Stack
* **Frameworks:** [PyTorch](https://pytorch.org/), Opacus (for Differential Privacy).
* **Privacy Mechanism:** PATE (Private Aggregation of Teacher Ensembles).
* **Analysis:** Formal Privacy Budgeting ($\epsilon, \delta$ differential privacy).

### Core Features
* High-Accuracy Privacy: Achieved **85.5% test accuracy** on sensitive financial data while maintaining strict differential privacy guarantees.
* Trade-off Analysis: Led the investigation into how varying noise multipliers and clipping gradients affect the convergence of deep learning models.
