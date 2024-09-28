---
title: 'Beyond Concept Bottleneck Models: How to Make Black Boxes Intervenable?'
authors:
- Ričards Marcinkevičs*
- Sonia Laguna*
- admin
- Julia Vogt


abstract: Recently, interpretable machine learning has re-explored concept bottleneck models (CBM). An advantage of this model class is the user's ability to intervene on predicted concept values, affecting the downstream output. In this work, we introduce a method to perform such concept-based interventions on pretrained neural networks, which are not interpretable by design, only given a small validation set with concept labels. Furthermore, we formalise the notion of intervenability as a measure of the effectiveness of concept-based interventions and leverage this definition to fine-tune black boxes. Empirically, we explore the intervenability of black-box classifiers on synthetic tabular and natural image benchmarks. We focus on backbone architectures of varying complexity, from simple, fully connected neural nets to Stable Diffusion. We demonstrate that the proposed fine-tuning improves intervention effectiveness and often yields better-calibrated predictions. To showcase the practical utility of our techniques, we apply them to deep chest X-ray classifiers and show that fine-tuned black boxes are more intervenable than CBMs. Lastly, we establish that our methods are still effective under vision-language-model-based concept annotations, alleviating the need for a human-annotated validation set.

url_pdf: https://arxiv.org/abs/2401.13544


date: '2024-09-12'
lastmod: '2024-09-28'
publishDate: '2024-09-28T09:59:44.404433Z'
publication_types:
- paper-conference
publication: '*Advances in Neural Information Processing Systems 37 (NeurIPS 2024)*'
---
