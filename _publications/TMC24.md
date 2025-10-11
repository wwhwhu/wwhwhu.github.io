---
title: "PriFairFed: A local differentially private federated learning algorithm for client-level fairnes"
collection: publications
category: manuscripts
permalink: /publication/mimir
excerpt: 'This paper is about using local differential privacy (LDP) to enhance client-level performance fairness in federated learning systems.'
date: 2024-12-13
venue: 'IEEE Transactions on Mobile Computing'
link: 'https://doi.org/10.1109/TMC.2024.3516813'
paperurl: 'http://wwhwhu.github.io/files/TMC24.pdf'
bibtexurl: 'http://wwhwhu.github.io/files/TMC24.bib'
citation: 'Hu, Chuang, et al. "PriFairFed: A local differentially private federated learning algorithm for client-level fairness." IEEE Transactions on Mobile Computing (2024).'
---

Local Differential Privacy (LDP) is a mechanism used to protect training privacy in Federated Learning (FL) systems, typically by introducing noise to data and local models. However, in real-world distributed edge systems, the non-independent and identically distributed nature of data means that clients in FL systems experience varying sensitivities to LDP-introduced noise. This disparity leads to fairness issues, potentially discouraging marginal clients from contributing further. In this paper, we explore how to enhance client-level performance fairness under LDP conditions. We model an FL system with LDP and formulate the problem PriFair using regularization, which assigns varied noise amplitudes to clients based on federated analytics. Additionally, we develop PriFairFed, a Tikhonov regularization-based algorithm that eliminates variable dependencies and optimizes variables alternately, while also offering a theoretical privacy guarantee. We further experimented with the algorithm on a real-world system with 20 Raspberry Pi clients, showing up to a 73.2% improvement in client-level fairness compared to existing state-of-the-art approaches, while maintaining a comparable level of privacy.