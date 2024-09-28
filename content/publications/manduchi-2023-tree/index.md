---
title: Tree Variational Autoencoders
authors:
- Laura Manduchi*
- admin copy
- Alain Ryser
- Julia Vogt


abstract: We propose Tree Variational Autoencoder (TreeVAE), a new generative hierarchical clustering model that learns a flexible tree-based posterior distribution over latent variables. TreeVAE hierarchically divides samples according to their intrinsic characteristics, shedding light on hidden structures in the data. It adapts its architecture to discover the optimal tree for encoding dependencies between latent variables. The proposed tree-based generative architecture enables lightweight conditional inference and improves generative performance by utilizing specialized leaf decoders. We show that TreeVAE uncovers underlying clusters in the data and finds meaningful hierarchical relations between the different groups on a variety of datasets, including real-world imaging data. We present empirically that TreeVAE provides a more competitive log-likelihood lower bound than the sequential counterparts. Finally, due to its generative nature, TreeVAE is able to generate new samples from the discovered clusters via conditional sampling.

url_pdf: https://arxiv.org/abs/2306.08984

date: '2023-12-20'
lastmod: '2024-09-28'
publishDate: '2024-09-28T09:59:44.392636Z'
publication_types:
- paper-conference
publication: '*Spotlight @ Advances in Neural Information Processing Systems 36 (NeurIPS
  2023)*'
---
