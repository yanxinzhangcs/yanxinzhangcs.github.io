---
title: "Top-r Influential Community Search in Bipartite Graphs"
authors: Yanxin Zhang, Zhengyu Hua, Long Yuan
collection: publications
date: 2025-09-01
venue: "VLDB Workshops 2025 Best Paper"
permalink: /publications/topr-influential-community/
pdf: https://www.vldb.org/2025/Workshops/VLDB-Workshops-2025/LSGDA/LSGDA25_02.pdf
arxiv: https://arxiv.org/abs/2412.06216
doi: https://doi.org/10.48550/arXiv.2412.06216
citation: 'Zhang, Y., Hua, Z., Yuan, L. "Top-r Influential Community Search in Bipartite Graphs." In *Proceedings of the VLDB Workshops 2025 (LSGDA)*, also available as arXiv preprint arXiv:2412.06216.'
---

**Abstract.**  
Community search over bipartite graphs is a fundamental problem, and finding influential communities has attracted significant attention. However, all existing studies have used the minimum weight of vertices as the influence of communities. This leads to an inaccurate assessment of real influence in graphs where there are only a few vertices with low weights. In this paper, we propose a new cohesive subgraph model named (k,l)-influential community that considers the average weight of vertices from two layers on bipartite graphs, thereby providing a more comprehensive reflection of community influence. Based on this community model, we present a recursive algorithm that traverses the entire bipartite graph to find top-(k,l)-influential communities. To further expedite the search for influential communities, we propose a slim tree structure to reduce the search width and introduce several effective upper bounds to reduce the search depth. Since we have proven that this problem is NP-hard, using exact algorithms to find top-(k,l)-communities accurately is very time-consuming. Therefore, we propose an approximate algorithm using a greedy approach to find top-(k,l)-communities as quickly as possible. It only takes O(n log n) time. Additionally, we introduce a new pruning algorithm to improve the efficiency of the search. Extensive experiments on 10 real-world graphs validate both the effectiveness and the efficiency of our algorithms.

[PDF (VLDB Workshop)](https://www.vldb.org/2025/Workshops/VLDB-Workshops-2025/LSGDA/LSGDA25_02.pdf){: .btn .btn--primary }  
[arXiv](https://arxiv.org/abs/2412.06216){: .btn }  
[DOI](https://doi.org/10.48550/arXiv.2412.06216){: .btn }