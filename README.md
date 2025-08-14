🌀 Denoising Diffusion Probabilistic Model (DDPM) in PyTorch

This repository contains a full PyTorch implementation of a Denoising Diffusion Probabilistic Model (DDPM) to generate 64x64 images of human faces.
A generative model that synthesizes images by iteratively denoising from pure Gaussian noise.
The implementation is inspired by Ho et al., 2020 (https://hojonathanho.github.io/diffusion/assets/denoising_diffusion20.pdf) and extended with modern improvements like cosine beta scheduling, EMA weights, and a flexible UNet backbone.
