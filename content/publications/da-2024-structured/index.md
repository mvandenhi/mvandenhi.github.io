---
title: 'Structured Generations: Using Hierarchical Clusters to guide Diffusion Models'
authors:
- Jorge da Silva Gonçalves
- Laura Manduchi
- admin
- Julia E Vogt


abstract: This paper introduces Diffuse-TreeVAE, a deep generative model that integrates hierarchical clustering into the framework of Denoising Diffusion Probabilistic Models (DDPMs). The proposed approach generates new images by sampling from a root embedding of a learned latent tree VAE-based structure, it then propagates through hierarchical paths, and utilizes a second-stage DDPM to refine and generate distinct, high-quality images for each data cluster. The result is a model that not only improves image clarity but also ensures that the generated samples are representative of their respective clusters, addressing the limitations of previous VAE-based methods and advancing the state of clustering-based generative modeling.

url_pdf: https://arxiv.org/abs/2407.06124
date: '2024-07-25'
lastmod: '2024-09-28'
publishDate: '2024-09-28T09:59:44.422857Z'
publication_types:
- paper-conference
publication: '*ICML 2024 Workshop on Structured Probabilistic Inference & Generative
  Modeling*'
---
