# Stochastic Variational Inference and Variational Autoencoders

## Overview
This project explores **Stochastic Variational Inference (SVI)** and its application to **Variational Autoencoders (VAEs)**. The goal is to understand how variational inference scales to large datasets and how stochastic optimization enables efficient approximate Bayesian inference in latent-variable models.

The repository focuses on both **theoretical formulation** and **practical implementation**, emphasizing the connection between classical variational inference and modern deep generative models.

---

## Topics Covered

### 1. Variational Inference
- Evidence Lower Bound (ELBO) formulation
- Mean-field variational families
- Coordinate ascent vs. gradient-based optimization
- Reparameterization trick for low-variance gradient estimates

---

### 2. Stochastic Variational Inference (SVI)
- Mini-batch–based optimization of the ELBO
- Stochastic gradients and unbiased estimators
- Scalability to large datasets
- Convergence behavior and optimization stability


---

### 3. Variational Autoencoders (VAE)
- Latent-variable generative modeling
- Encoder–decoder architecture
- Gaussian latent space assumptions
- ELBO as a reconstruction–regularization trade-off

The implementation demonstrates how VAEs can be viewed as a special case of stochastic variational inference with amortized inference.

---

## Experiments and Analysis
- Training dynamics under different learning rates and batch sizes
- Effect of latent dimension on reconstruction quality
- Behavior of the KL divergence term during optimization
- Qualitative inspection of generated samples
