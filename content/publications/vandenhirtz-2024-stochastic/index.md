---
title: Stochastic Concept Bottleneck Models

authors:
- admin copy
- Sonia Laguna*
- Ričards Marcinkevičs
- Julia E Vogt

abstract: Concept Bottleneck Models (CBMs) have emerged as a promising interpretable method whose final prediction is based on intermediate, human-understandable concepts rather than the raw input. Through time-consuming manual interventions, a user can correct wrongly predicted concept values to enhance the model's downstream performance. We propose Stochastic Concept Bottleneck Models (SCBMs), a novel approach that models concept dependencies. In SCBMs, a single-concept intervention affects all correlated concepts, thereby improving intervention effectiveness. Unlike previous approaches that model the concept relations via an autoregressive structure, we introduce an explicit, distributional parameterization that allows SCBMs to retain the CBMs' efficient training and inference procedure. Additionally, we leverage the parameterization to derive an effective intervention strategy based on the confidence region. We show empirically on synthetic tabular and natural image datasets that our approach improves intervention effectiveness significantly. Notably, we showcase the versatility and usability of SCBMs by examining a setting with CLIP-inferred concepts, alleviating the need for manual concept annotations. 
url_pdf: https://arxiv.org/abs/2406.19272

date: '2024-10-12'
lastmod: '2024-09-28'
publishDate: '2024-09-28T10:59:44.416491Z'
publication_types:
- article-journal
publication: '*Advances in Neural Information Processing Systems 37 (NeurIPS 2024)*'
---
