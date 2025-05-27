---
title: "Graph Fairness via Authentic Counterfactuals: Tackling Structural and Causal Challenges"
collection: publications
category: paper
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'Zichong Wang, **Zhipeng Yin**, Fang Liu, Zhen Liu, Christine Lisetti, Rui Yu, Shaowei Wang, Jun Liu, Sukumar Ganapati, Shuigeng Zhou and Wenbin Zhang'
date: 2025-02-17
venue: 'ACM SIGKDD Explorations Newsletter'
paperurl: 'chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://www.kdd.org/exploration_files/p89-Graph-fairness-Counterfactual.pdf'
---

The extensive use of graph-based Machine Learning (ML) decision-making systems has raised numerous concerns about their potential discrimination, especially in domains with high societal impact. Various fair graph methods have thus been proposed, primarily relying on statistical fairness notions that emphasize sensitive attributes as a primary source of bias, leaving other sources of bias inadequately addressed. Existing works employ counterfactual fairness to tackle this issue from a causal perspective. However, these approaches suffer from two key limitations: they overlook hidden confounders that may affect node features and graph structure, leading to an oversimplification of causality and the inability to generate authentic counterfactual instances; they neglect graph structure bias, resulting in over-correlation of sensitive attributes with node representations. In response, this paper introduces the Authentic Graph Counterfactual Generator (AGCG), a novel framework designed to mitigate graph structure bias through a novel fair message passing technique and to improve counterfactual sample generation by inferring hidden confounders. Comprising four key modules– subgraph selection, fair node aggregation, hidden confounder identification, and counterfactual instance generation– AGCG offers a holistic approach to advancing graph model fairness in multiple dimensions. Empirical studies conducted on both real and synthetic datasets demonstrate the effectiveness and utility of AGCG in promoting fair graph-based decision-making.