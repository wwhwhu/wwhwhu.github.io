---
title: "Beyond Sharp Minima: Robust LLM Unlearning via Feedback-Guided Multi-Point Optimization"
collection: publications
category: preprints
permalink: /publication/aegis
excerpt: 'This paper is about how to make LLM unlearning more robust against relearning and jailbreaking attacks.'
date: 2025-09-30
venue: 'Preprint on ArXiv'
paperurl: 'http://whuwwh.github.io/files/Arxiv25.pdf'
bibtexurl: 'https://whuwwh.github.io/files/Arxiv25.bib'
link: 'https://arxiv.org/abs/2509.20230'
citation: '<strong>Wenhan Wu</strong>, et al. "Beyond Sharp Minima: Robust LLM Unlearning via Feedback-Guided Multi-Point Optimization." arXiv preprint arXiv:2509.20230 (2025).'
---

<div style="text-align: justify;">
<strong>Abstract:</strong>: Current LLM unlearning methods face a critical security vulnerability that undermines their fundamental purpose: while they appear to successfully remove sensitive or harmful knowledge, this ``forgotten" information remains precariously recoverable through relearning attacks. We identify that the root cause is that conventional methods optimizing the forgetting loss at individual data points will drive model parameters toward sharp minima in the loss landscape. In these unstable regions, even minimal parameter perturbations can drastically alter the model's behaviors. Consequently, relearning attacks exploit this vulnerability by using just a few fine-tuning samples to navigate the steep gradients surrounding these unstable regions, thereby rapidly recovering knowledge that was supposedly erased. This exposes a critical robustness gap between apparent unlearning and actual knowledge removal. To address this issue, we propose StableUN, a bi-level feedback-guided optimization framework that explicitly seeks more stable parameter regions via neighborhood-aware optimization. It integrates forgetting feedback, which uses adversarial perturbations to probe parameter neighborhoods, with remembering feedback to preserve model utility, aligning the two objectives through gradient projection. Experiments on WMDP and MUSE benchmarks demonstrate that our method is significantly more robust against both relearning and jailbreaking attacks while maintaining competitive utility performance.
</div>