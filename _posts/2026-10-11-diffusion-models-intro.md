---
title: 'An Introduction to Diffusion Models'
date: 2026-10-11
permalink: /posts/2026/10/diffusion-models-intro/
tags:
  - diffusion-models
  - generative-models
---

This is a introduction of diffusion model

## Principle

$$p_\theta(x_{t-1} \mid x_t)$$


$$
q(x_t \mid x_{t-1}) = \mathcal{N}(x_t; \sqrt{1-\beta_t}\, x_{t-1}, \beta_t I)
$$

```python
import torch
```
