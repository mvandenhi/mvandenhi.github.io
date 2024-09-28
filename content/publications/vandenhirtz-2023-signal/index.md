---
title: 'Signal Is Harder To Learn Than Bias: Debiasing with Focal Loss'
authors:
- admin
- Laura Manduchi
- Ričards Marcinkevičs
- Julia E Vogt

abstract: Spurious correlations are everywhere. While humans often do not perceive them, neural networks are notorious for learning unwanted associations, also known as biases, instead of the underlying decision rule. As a result, practitioners are often unaware of the biased decision-making of their classifiers. Such a biased model based on spurious correlations might not generalize to unobserved data, leading to unintended, adverse consequences. We propose Signal is Harder (SiH), a variational-autoencoder-based method that simultaneously trains a biased and unbiased classifier using a novel, disentangling reweighting scheme inspired by the focal loss. Using the unbiased classifier, SiH matches or improves upon the performance of state-of-the-art debiasing methods. To improve the interpretability of our technique, we propose a perturbation scheme in the latent space for visualizing the bias that helps practitioners become aware of the sources of spurious correlations.

url_pdf: https://arxiv.org/abs/2305.19671

date: '2023-05-04'
lastmod: '2024-09-28'
publishDate: '2024-09-28T09:59:44.386520Z'
publication_types:
- paper-conference
publication: '*Spotlight @ Domain Generalization Workshop at ICLR 2023*'
---
