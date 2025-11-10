---
title: "REMISVFU: Vertical Federated Unlearning via Representation Misdirection for Intermediate Output Feature"
collection: publications
category: conferences
permalink: /publication/VFU
excerpt: 'This paper is about a representation misdirection based unlearning framework in vertical federated learning systems.'
date: 2026-01-20
venue: 'The 40th AAAI Conference on Artificial Intelligence'
paperurl: 'http://whuwwh.github.io/files/AAAI26.pdf'
bibtexurl: 'https://whuwwh.github.io/files/AAAI26.bib'
citation: '<strong>Wenhan Wu</strong>, et al. "REMISVFU: Vertical Federated Unlearning via Representation Misdirection for Intermediate Output Feature." 2026 40th AAAI Conference on Artificial Intelligence. AAAI, 2026.'
---

<div style="text-align: justify;">
<strong>Abstract:</strong>: Data-protection regulations such as the GDPR grant every participant in a federated system a right to be forgotten. Federated unlearning has therefore emerged as a research frontier, aiming to remove a specific party’s contribution from the learned model while preserving the utility of the remaining parties. However, most unlearning techniques focus on Horizontal Federated Learning (HFL), where data are partitioned by samples. In contrast, Vertical Federated Learning (VFL) allows organizations that possess complementary feature spaces to train a joint model without sharing raw data. The resulting feature-partitioned architecture renders HFLoriented unlearning methods ineffective. In this paper, we propose REMISVFU, a plug-and-play representation misdirection framework that enables fast, client-level unlearning in splitVFL systems. When a deletion request arrives, the forgetting party collapses its encoder output to a randomly sampled anchor on the unit sphere, severing the statistical link between its features and the global model. To maintain utility for the remaining parties, the server jointly optimizes a retention loss and a forgetting loss, aligning their gradients via orthogonal projection to eliminate destructive interference. Evaluations on public benchmarks show that REMISVFU suppresses back-door attack success to the natural class-prior level and sacrifices only about 2.5% points of clean accuracy, outperforming state-of-the-art baselines.
</div>