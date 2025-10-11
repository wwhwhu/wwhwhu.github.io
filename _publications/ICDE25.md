---
title: "Defending against Attribute Inference Attacks in Post-Training of Recommendation Systems via Unlearning"
collection: publications
category: conferences
permalink: /publication/attrU
excerpt: 'This paper is about the dual-opjective attribute unlearning in recommendation systems.'
date: 2025-08-20
venue: 'IEEE 41st International Conference on Data Engineering (ICDE)'
paperurl: 'http://whuwwh.github.io/files/ICDE25.pdf'
bibtexurl: 'https://whuwwh.github.io/files/ICDE25.bib'
posterurl: 'http://whuwwh.github.io/files/ICDE25_Poster.pdf'
slidesurl: 'http://whuwwh.github.io/files/ICDE25_Slides.pdf'
link: 'https://doi.org/10.1109/ICDE65448.2025.00200'
citation: '<strong>Wenhan Wu</strong>, et al. "Defending against Attribute Inference Attacks in Post-Training of Recommendation Systems via Unlearning." 2025 IEEE 41st International Conference on Data Engineering (ICDE). IEEE, 2025.'
---

<div style="text-align: justify;">
<strong>Abstract:</strong>: Attribute Inference Attacks (AIAs) pose a significant threat to recommendation systems (RS) by enabling adversaries to use threat models to infer sensitive user attributes like gender or race from user embeddings, resulting in privacy breaches such as unauthorized profiling and discriminatory policies against specific groups. Existing attribute protection methods are primarily applied during training, suffering from significant limitations, such as architectural inflexibility, dependence on interaction data, and potential catastrophic degradation in recommendation performance. To overcome these challenges, we propose AttrCloak, an efficient and effective post-training attribute unlearning (AU) framework that removes sensitive information from user embeddings without altering RS training architectures. AttrCloak employs dual-objective optimization with parameter self-sharing to minimize mutual information between user embeddings and sensitive attributes while preserving recommendation quality. Furthermore, it accommodates data-free scenarios by leveraging regularization loss when interaction data is unavailable. Comprehensive evaluations on four real-world datasets demonstrate AttrCloak's good performance in privacy protection and recommendation performance.
</div>