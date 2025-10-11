---
title: "Aegis: Post-Training Attribute Unlearning in Federated Recommender Systems against Attribute Inference Attacks"
collection: publications
category: conferences
permalink: /publication/aegis
excerpt: 'This paper is about the attribute-wise privacy protection in FedRecs against attribute inference attacks.'
date: 2025-04-28
venue: 'Proceedings of the ACM on Web Conference (WWW)'
paperurl: 'http://whuwwh.github.io/files/WWW25.pdf'
bibtexurl: 'https://whuwwh.github.io/files/WWW25.bib'
posterurl: 'http://whuwwh.github.io/files/WWW25_Poster.pdf'
link: 'https://dl.acm.org/doi/abs/10.1145/3696410.3714823'
citation: '<strong>Wenhan Wu</strong>, Jiawei Jiang, and Chuang Hu. "Aegis: Post-Training Attribute Unlearning in Federated Recommender Systems against Attribute Inference Attacks." Proceedings of the ACM on Web Conference 2025.'
---

<div style="text-align: justify;">
<strong>Abstract:</strong>: As privacy concerns in recommender systems become increasingly prominent, federated recommender systems (FedRecs) have emerged as a promising distributed training paradigm. FedRecs enable the collaborative training of a shared global recommendation model without requiring the exchange of raw client interaction data. However, models trained using standard FedRec methods remain vulnerable to personal information leakage, particularly through attribute inference attacks, which can expose sensitive user attributes such as gender and race. In this paper, we address these user-sensitive attributes as targets for federated unlearning. To protect users' sensitive information, attribute unlearning aims to eliminate sensitive attributes from user embeddings, thereby preventing inference attacks while preserving recommendation performance. We introduce a novel post-training federated unlearning framework, Aegis, which performs unlearning based on private attribute requests after the model has been trained, minimizing the degradation in recommendation accuracy. Aegis employs an information-theoretic multi-component loss function to balance privacy protection and recommendation performance. Additionally, Aegis adapts to scenarios where training interaction data may be unavailable, reflecting real-world centralized protection scenarios. Comprehensive evaluations of various benchmark datasets demonstrate that our proposed method effectively safeguards user privacy while maintaining high-quality recommendations.
</div>