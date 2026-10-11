---
title: 'An Introduction to Diffusion Models'
date: 2026-10-11
permalink: /posts/2026/10/diffusion-models-intro/
tags:
  - diffusion-models
  - generative-models
---

这里开始写正文，用普通的 Markdown 语法。

## 小标题

公式用两个美元符号包起来：$$p_\theta(x_{t-1} \mid x_t)$$

单独成行的公式：

$$
q(x_t \mid x_{t-1}) = \mathcal{N}(x_t; \sqrt{1-\beta_t}\, x_{t-1}, \beta_t I)
$$

```python
import torch
print("代码块会自动高亮")
```
