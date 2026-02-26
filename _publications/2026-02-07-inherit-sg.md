---
title: "INHerit-SG: Incremental Hierarchical Semantic Scene Graphs with RAG-Style Retrieval"
collection: publications
category: conferences
permalink: /publication/2026-02-07-inherit-sg
excerpt: 'A semantic mapping work under review.'
date: 2026-02-07
venue: 'Under Review'
paperurl: 'https://arxiv.org/abs/2602.12971'
citation: '<b>Yuk Tung Samuel Fang</b>, Zhikang Shi, Jiabin Qiu, Zixuan Chen, Jieqi Shi, Hao Xu, Jing Huo, Yang Gao. (2025). &quot;INHerit-SG: Incremental Hierarchical Semantic Scene Graphs with RAG-Style Retrieval.&quot; <i>Under Review</i>.'
image: '/images/inherit_sg_teaser.png'
abstract: 'Driven by advancements in foundation models, semantic scene graphs have emerged as a prominent paradigm for high-level 3D environmental abstraction in robot navigation. However, existing approaches are fundamentally misaligned with the needs of embodied tasks. As they rely on either offline batch processing or implicit feature embeddings, the maps can hardly support interpretable human-intent reasoning in complex environments. To address these limitations, we present INHerit-SG. We redefine the map as a structured, RAG-ready knowledge base where natural-language descriptions are introduced as explicit semantic anchors to better align with human intent. An asynchronous dual-process architecture, together with a Floor-Room-Area-Object hierarchy, decouples geometric segmentation from time-consuming semantic reasoning. An event-triggered map update mechanism reorganizes the graph only when meaningful semantic events occur. This strategy enables our graph to maintain long-term consistency with relatively low computational overhead. For retrieval, we deploy multi-role Large Language Models (LLMs) to decompose queries into atomic constraints and handle logical negations, and employ a hard-to-soft filtering strategy to ensure robust reasoning. This explicit interpretability improves the success rate and reliability of complex retrievals, enabling the system to adapt to a broader spectrum of human interaction tasks. We evaluate INHerit-SG on a newly constructed dataset, HM3DSem-SQR, and in real-world environments. Experiments demonstrate that our system achieves state-of-the-art performance on complex queries, and reveal its scalability for downstream navigation tasks.'
---
This paper presents INHerit-SG, an incremental hierarchical semantic scene graph generation method with RAG-style retrieval capabilities.
