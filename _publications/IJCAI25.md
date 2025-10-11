---
title: "Zero-shot Federated Unlearning via Transforming from Data-Dependent to Personalized Model-Centric"
collection: publications
category: conferences
permalink: /publication/zeroFU
excerpt: 'This paper is about the zero-shot federated unlearning.'
date: 2025-08-31
venue: 'Proceedings of the Thirty-Fourth International Joint Conference on Artificial Intelligence (IJCAI)'
paperurl: 'http://whuwwh.github.io/files/IJCAI25.pdf'
bibtexurl: 'https://whuwwh.github.io/files/IJCAI25.bib'
posterurl: 'http://whuwwh.github.io/files/IJCAI25_Poster.pdf'
slidesurl: 'http://whuwwh.github.io/files/IJCAI25_Slides.pdf'
link: 'https://doi.org/10.24963/ijcai.2025/733'
citation: '<strong>Wenhan Wu</strong>, et al. Zero-shot Federated Unlearning via Transforming from Data-Dependent to Personalized Model-Centric.'
---

<div style="text-align: justify;">
<strong>Abstract:</strong>: Federated Unlearning (FU) addresses the "right to be forgotten" in federated learning by removing specific client data's contribution without retraining from scratch. Existing FUs are data-dependent, which make the assumption that systems can access original training data or stored historical parameter updates during unlearning. However, the assumption cannot always hold in practice, as users usually request the deletion of client data and historical parameter updates due to privacy concerns or storage limitations. Therefore, it is crucial to develop a zero-shot FU method without such data access. The key challenge is how to distinguish and remove the impact of target clients without data-level information. Motivated by the idea that if we can learn client-specific personalized information from the model instead of data, FU can be model-centric and data-free, we present the first zero-shot FU framework ZeroFU. By embedding client contributions into the model during learning via condition computation, ZeroFU enables the model to possess personalized features for unlearning. The unlearning is achieved using a proposed GAN-based distillation framework that obfuscates the personalized feature of the target client. Evaluations demonstrate its effectiveness in unlearning under non-IID settings.
</div>