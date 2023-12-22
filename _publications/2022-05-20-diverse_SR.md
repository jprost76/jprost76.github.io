---
title: "Efficient posterior sampling for diverse super-resolution
with hierarchical VAE Prior"
collection: Preprint
permalink: /publication/2022-05-20-diverse_SR
excerpt: 'We investigate the problem of producing diverse solutions to an image super-resolution problem.
From a probabilistic perspective, this can be done by sampling from the posterior distribution of an
inverse problem, which requires the definition of a prior distribution on the high-resolution images.
In this work, we propose to use a pretrained hierarchical variational autoencoder (HVAE) as a prior.
We train a lightweight stochastic encoder to encode low-resolution images in the latent space of a
pretrained HVAE. At inference, we combine the low-resolution encoder and the pretrained generative
model to super-resolve an image. We demonstrate on the task of face super-resolution that our method
provides an advantageous trade-off between the computational efficiency of conditional normalizing
flows techniques and the sample quality of diffusion based methods.'
date: 2024-02-20
venue: '19th International Joint Conference on Computer Vision Theory and Applications (VISAPP2024)'
paperurl: ''
preprint: 'https://arxiv.org/pdf/2205.10347'
code: ''
citation: 'Jean Prost, Antoine Houdard, Nicolas Papadakis, Andrés Almansa'
---

We investigate the problem of producing diverse solutions to an image super-resolution problem.
From a probabilistic perspective, this can be done by sampling from the posterior distribution of an
inverse problem, which requires the definition of a prior distribution on the high-resolution images.
In this work, we propose to use a pretrained hierarchical variational autoencoder (HVAE) as a prior.
We train a lightweight stochastic encoder to encode low-resolution images in the latent space of a
pretrained HVAE. At inference, we combine the low-resolution encoder and the pretrained generative
model to super-resolve an image. We demonstrate on the task of face super-resolution that our method
provides an advantageous trade-off between the computational efficiency of conditional normalizing
flows techniques and the sample quality of diffusion based methods.

[Arxiv link](https://arxiv.org/pdf/2205.10347)