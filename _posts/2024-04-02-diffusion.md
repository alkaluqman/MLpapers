---
layout: post
title:  Diffusion Models
---

<div class="message">
  Latent diffusion, stable diffusion
</div>

A diffusion model is a *parametrized Markov chain* trained using variational inference to 
generate sample images from noise.    
What is variational inference? Approximate guessing. Variational inference is the process of 
using an approximate posterior distribution instead of a complex true data distribution.   
To ensure the approximations KL, divergence between the 2 distributions are minimized. 
Minimizing KL divergence is equal to maximizing ELBO and vice versa.   

Denoising diffusion models have 2 processes:
1. Forward diffusion process
2. Reverse denoising process
<p align="center">
    <img src="public/post_images/diffusion.png" alt="Denoising diffusion">
</p>   

Each of the intermediate step is a latent variable.
<p align="center">
    <img src="public/post_images/blog-diffusion.png" alt="Denoising diffusion">
</p>   



### References:
- Thermodynamics inspired original [paper](https://arxiv.org/pdf/2006.11239.pdf)