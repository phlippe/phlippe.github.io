---
title: "Categorical Normalizing Flows via Continuous Transformations"
collection: publications
permalink: /publication/2020-06-17-categorical-normalizing-flows
excerpt: 'We introduce Categorical Normalizing Flows, i.e. continuous normalizing flows on categorical data.'
date: 2020-06-17
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2006.09790'
citation: 'Lippe, Phillip, and Efstratios Gavves. "Categorical Normalizing Flows via Continuous Transformations." <i>arXiv preprint arXiv:2006.09790</i> (2020).'
---
Despite their popularity, to date, the application of normalizing flows on categorical data stays limited. The current practice of using dequantization to map discrete data to a continuous space is inapplicable as categorical data has no intrinsic order. Instead, categorical data have complex and latent relations that must be inferred, like the synonymy between words. In this paper, we investigate Categorical Normalizing Flows, that is normalizing flows for categorical data. By casting the encoding of categorical data in continuous space as a variational inference problem, we jointly optimize the continuous representation and the model likelihood. To maintain unique decoding, we learn a partitioning of the latent space by factorizing the posterior. Meanwhile, the complex relations between the categorical variables are learned by the ensuing normalizing flow, thus maintaining a close-to exact likelihood estimate and making it possible to scale up to a large number of categories. Based on Categorical Normalizing Flows, we propose GraphCNF a permutation-invariant generative model on graphs, outperforming both one-shot and autoregressive flow-based state-of-the-art on molecule generation.

<i>BibTeX entry:</i>
```
@article{lippe2020CNFs,
  title={Categorical Normalizing Flows via Continuous Transformations},
  author={Lippe, Phillip and Gavves, Efstratios},
  journal={arXiv preprint arXiv:2006.09790},
  year={2020}
}
```