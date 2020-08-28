---
title: "Diversifying Task-oriented Dialogue Response Generation with Prototype Guided Paraphrasing"
collection: publications
permalink: /publication/2020-08-07-dialogue-response-generation
excerpt: 'Combining template- and corpus-based systems for diverse, consistent dialogues'
date: 2020-08-07
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2008.03391'
citation: 'Lippe, Phillip, et al. "Diversifying Task-oriented Dialogue Response Generation with Prototype Guided Paraphrasing." <i>arXiv preprint arXiv:2008.03391</i> (2020).'
---
Existing methods for Dialogue Response Generation (DRG) in Task-oriented Dialogue Systems (TDSs) can be grouped into two categories: template-based and corpus-based. The former prepare a collection of response templates in advance and fill the slots with system actions to produce system responses at runtime. The latter generate system responses token by token by taking system actions into account. While template-based DRG provides high precision and highly predictable responses, they usually lack in terms of generating diverse and natural responses when compared to (neural) corpus-based approaches. Conversely, while corpus-based DRG methods are able to generate natural responses, we cannot guarantee their precision or predictability. Moreover, the diversity of responses produced by today's corpus-based DRG methods is still limited. We propose to combine the merits of template-based and corpus-based DRGs by introducing a prototype-based, paraphrasing neural network, called P2-Net, which aims to enhance quality of the responses in terms of both precision and diversity. Instead of generating a response from scratch, P2-Net generates system responses by paraphrasing template-based responses. To guarantee the precision of responses, P2-Net learns to separate a response into its semantics, context influence, and paraphrasing noise, and to keep the semantics unchanged during paraphrasing. To introduce diversity, P2-Net randomly samples previous conversational utterances as prototypes, from which the model can then extract speaking style information. We conduct extensive experiments on the MultiWOZ dataset with both automatic and human evaluations. The results show that P2-Net achieves a significant improvement in diversity while preserving the semantics of responses.

BibTeX entry:
```
@article{lippe2020diversifying,
  title={Diversifying Task-oriented Dialogue Response Generation with Prototype Guided Paraphrasing},
  author={Lippe, Phillip and Ren, Pengjie and Haned, Hinda and Voorn, Bart and de Rijke, Maarten},
  journal={arXiv preprint arXiv:2008.03391},
  year={2020}
}
```