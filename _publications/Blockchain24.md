---
title: "Frustum: Achieving High Throughput in Blockchain Systems through Hierarchical and Pipelined Sharding"
collection: publications
category: manuscripts
permalink: /publication/frustum
excerpt: 'This paper is about increasing the throughput of blockchain systems through hierarchical and pipelined sharding.'
date: 2024-04-12
venue: 'Blockchain'
link: 'https://doi.org/10.55092/blockchain20240002'
paperurl: 'http://wwhwhu.github.io/files/blockchain.pdf'
bibtexurl: 'http://wwhwhu.github.io/files/blockchain.bib'
citation: 'Xu Y, <strong>Wu W</strong>, Gong Y, Ye Wang K, Hu C, et al. Frustum: achieving high throughput in blockchain systems through hierarchical and pipelined sharding. Blockchain 2024(1):0002.'
---

Sharding, breaking nodes into smaller groups, aims to enhance the scalability of traditional blockchain systems by allowing parallel transaction processing. However, existing sharding methods face challenges, including heavy inter-shard communication, re-sharding overhead, and low consensus concurrency. These limitations ultimately result in less desired system performance. To address these challenges, we propose Frustum, a novel hierarchical and pipelined sharding blockchain system. It separates shards into two layers: top L-Shard and base F-Shards. In each round, a global leader is elected from L-Shard and broadcasts a new block to F-Shard nodes, negating the need for final committee confirmation and simplifying the consensus process. Additionally, Frustum adopts a random re-sharding mechanism to mitigate the re-sharding overhead issue. Finally, Frustum employs a pipelined structure for enhanced consensus concurrency. Our Frustum prototype demonstrates a substantial performance boost, improving transaction throughput by 2.79 and 1.68 times over existing sharding systems with 16 shards and 1024 nodes.