---
title: "Fairness-Aware Graph Representation Learning Without Complete Demographic Information"
collection: publications
category:   paper
permalink: /publication/ecml1
excerpt: 'Zichong Wang, **Zhipeng Yin**, Liping Yang, Jun Zhuang, Rui Yu, Qingzhao Kong and Wenbin Zhang'
date: 2025-05-27
venue: 'European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML-PKDD)'

---

Graph neural networks (GNNs) can amplify social biases inherent in graph data, exacerbating inequality and violating privacy rights, especially in high-risk applications. In response, numerous fair graph learning methods have been proposed in recent years. However, most of them assume access to demographic information, a requirement rarely met in practice due to privacy, legal, or regulatory restrictions. To overcome these limitations, this paper introduces a novel fair graph learning framework that mitigates bias in graph learning without using demographic information. Specifically, we first propose a mechanism to generate proxies for demographic information and then design a strategy to ensure consistent node embeddings across different demographic subgroups. Additionally, we propose an adaptivity confidence strategy that dynamically adjusts each node's contribution to fairness and utility based on prediction confidence. Through extensive experiments on multiple datasets and fair graph learning frameworks, we demonstrate the framework's effectiveness in both mitigating bias and maintaining model utility. This work advances the perspective of algorithmic fairness through the lens of unavailable demographic information, with potential for broader applications. 