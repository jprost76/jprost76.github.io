---
title: "Learning Local Regularization for Variational Image Restoration"
collection: publications
permalink: /publication/2021-01-05-learning_local_reg
excerpt: 'In this work, we propose a framework to learn a local regularization model for solving general image restoration problems. This regularizer is defined with a fully convolutional neural network that sees the image through a receptive field corresponding to small image patches. The regularizer is then learned as a critic between unpaired distributions of clean and degraded patches using a Wasserstein generative adversarial networks based energy. This yields a regularization function that can be incorporated in any image restoration problem. The efficiency of the framework is finally shown on denoising and deblurring applications.'
date: 2021-01-05
venue: 'Scale Space and Variational Methods in Computer Vision: 8th International Conference, (SSVM 2021)'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-75549-2_29'
preprint: 'https://arxiv.org/pdf/2102.06155'
code: 'https://github.com/jprost76/LocalReg'
citation: 'Jean Prost, Antoine Houdard, Andrés Almansa, Nicolas Papadakis'
---

In this work, we propose a framework to learn a local regularization model for solving general image restoration problems. This regularizer is defined with a fully convolutional neural network that sees the image through a receptive field corresponding to small image patches. The regularizer is then learned as a critic between unpaired distributions of clean and degraded patches using a Wasserstein generative adversarial networks based energy. This yields a regularization function that can be incorporated in any image restoration problem. The efficiency of the framework is finally shown on denoising and deblurring applications.
[arxiv link](https://arxiv.org/pdf/2102.06155), [github repo](https://github.com/jprost76/LocalReg)
