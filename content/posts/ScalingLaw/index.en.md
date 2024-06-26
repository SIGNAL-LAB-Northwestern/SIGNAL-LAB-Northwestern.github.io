---
title: "Scaling Law of Scientific Machine Learning"
date: 2022-05-12T09:40:28+08:00
draft: false
author: "Yiping"
tags: ["Scientific Machine Learning"]

lightgallery: true
---


## SCALE Lab's publicatoin in this direction

{{< admonition >}}
:(far fa-bookmark fa-fw): 
SCALE lab is always actively building scaling law for scientific machine learning, here's the achievement of lab members on this direction
- *Yiping Lu, Haoxuan Chen, Jianfeng Lu, Lexing Ying, Jose Blanchet* **Machine Learning For Elliptic PDEs: Fast Rate Generalization Bound, Neural Scaling Law and Minimax Optimality**, *Tenth International Conference on Learning Representations(ICLR) 2022*
- *Yiping Lu, Jose Blanchet,Lexing Ying* **Sobolev Acceleration and Statistical Optimality for Learning Elliptic Equations via Gradient Descent**, *Thirty-sixth Conference on Neural Information Processing Systems (NeurIPS) 2022*
- *Jikai Jin, Yiping Lu, Jose Blanchet, Lexing Ying*  **Minimax Optimal Kernel Operator Learning via Multilevel Training**, *Eleventh International Conference on Learning Representations(ICLR) 2023*
- *Honam Wong, Wendao Wu, Fanghui Liu, Yiping Lu*  	**Bengin overfitting in Fixed Dimension via Physics-Informed Learning with Smooth Inductive Bias**, *Submitted*

{{< /admonition >}}

## Scaling Law

The term “scaling laws” in deep learning refers to relations between functional properties of interest (usually the test loss or some performance metric for fine-tuning tasks) and properties of the architecture or optimization process (like model size, width, or training compute). These laws can help inform the design and training of deep learning models, as well as provide insights into their underlying principles.

![Research](./sclaing.png)

## Statistical Model For Physics Informed Machine Learning

### Physics-Informed Machine Learning
Physics-Informed Machine Learning (PIML) aims to solve equation \\(\mathcal{A}u=f\\) using observations of function \\(f\\).

### Operator Learning


## Inductive Bias

We also considered the following two estimators
- **Regularized Least Square** \\(\min_u ||\mathcal{A}(u)-f||^2\\)\\(+(||f||_\beta)^2\\)
- **Minimum Norm Interpolation**  \\(\min_u || f||_\beta\\) subject to \\((\mathcal{A}u)(x_i)=f(x_i)\\)
  
Here \\(||\cdot||_\beta\\) is the Sobolev norm.
