---
title: "Diverse super-resolution with pretrained deep hiererarchical VAEs"
collection: Preprint
permalink: /publication/2022-05-20-diverse_SR
excerpt: 'Image super-resolution is a one-to-many problem, but most deep-learning based methods only provide one single solution to this problem. In this work, we tackle the problem of diverse super-resolution by reusing VD-VAE, a state-of-the art variational autoencoder (VAE). We find that the hierarchical latent representation learned by VD-VAE naturally separates the image low-frequency information, encoded in the latent groups at the top of the hierarchy, from the image high-frequency details, determined by the latent groups at the bottom of the latent hierarchy. Starting from this observation, we design a super-resolution model exploiting the specific structure of VD-VAE latent space. Specifically, we train an encoder to encode low-resolution images in the subset of VD-VAE latent space encoding the low-frequency information, and we combine this encoder with VD-VAE generative model to sample diverse super-resolved version of a low-resolution input. We demonstrate the ability of our method to generate diverse solutions to the super-resolution problem on face super-resolution with upsampling factors x4, x8, and x16.'
date: 2022-05-20
venue: 'Preprint'
paperurl: 'https://arxiv.org/pdf/2205.10347'
citation: 'Jean Prost, Antoine Houdard, Nicolas Papadakis, Andrés Almansa'
---


Image super-resolution is a one-to-many problem, but most deep-learning based methods only provide one single solution to this problem. In this work, we tackle the problem of diverse super-resolution by reusing VD-VAE, a state-of-the art variational autoencoder (VAE). We find that the hierarchical latent representation learned by VD-VAE naturally separates the image low-frequency information, encoded in the latent groups at the top of the hierarchy, from the image high-frequency details, determined by the latent groups at the bottom of the latent hierarchy. Starting from this observation, we design a super-resolution model exploiting the specific structure of VD-VAE latent space. Specifically, we train an encoder to encode low-resolution images in the subset of VD-VAE latent space encoding the low-frequency information, and we combine this encoder with VD-VAE generative model to sample diverse super-resolved version of a low-resolution input. We demonstrate the ability of our method to generate diverse solutions to the super-resolution problem on face super-resolution with upsampling factors x4, x8, and x16.

[Arxiv link](https://arxiv.org/pdf/2205.10347)