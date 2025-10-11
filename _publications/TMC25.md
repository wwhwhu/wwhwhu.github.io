---
title: "Mimir: Data-free Federated Unlearning through Client-Specific Prompt Generation for Personalized Models"
collection: publications
category: manuscripts
permalink: /publication/mimir
excerpt: 'This paper is about data-free federated unlearning through client-specific prompt generation for personalized models.'
date: 2025-05-14
venue: 'IEEE Transactions on Mobile Computing'
link: 'https://doi.org/10.1109/TMC.2025.3570018'
paperurl: 'http://wwhwhu.github.io/files/TMC25.pdf'
bibtexurl: 'http://wwhwhu.github.io/files/TMC25.bib'
citation: 'Wu, Wenhan, et al. "Mimir: Data-Free Federated Unlearning Through Client-Specific Prompt Generation for Personalized Models." IEEE Transactions on Mobile Computing (2025).'
---

Federated unlearning (FU) has become an important area of research due to an increasing need for federated learning (FL) applications to comply with emerging data privacy regulations such as GDPR. It facilitates the removal of certain clients’ data from an already trained FL model while preserving the performance on the remaining client without the need to retrain from scratch. Existing FU methods typically require clients to have access to their training data or historical model updates, which may be impractical in real-world scenarios due to privacy constraints and changes in data availability. Moreover, FU methods may cause catastrophic unlearning, where removing a client’s data from heterogeneous, non-IID settings can negatively impact the model’s performance on data from retained clients. To address the aforementioned issues and leverage the capabilities of personalized federated learning (pFL) in handling non-IID data distributions, this paper introduce Mimir, a novel data-free federated unlearning framework designed for pFL settings. Mimir integrates both learning and unlearning phases by utilizing personalized prompts for each client. We design a distillation structure based on Generative Adversarial Networks (GANs) for client-level unlearning that does not require access to original data or historical updates. By leveraging client-specific prompts generated during the pFL phase, Mimir adapts to heterogeneous data distributions and mitigates catastrophic unlearning on the retained data. We demonstrate the effectiveness of Mimir through extensive experiments on benchmark datasets, showing its ability to forget target client data while preserving model accuracy on the remaining clients.