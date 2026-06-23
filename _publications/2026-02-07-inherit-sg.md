---
title: "INHerit-SG: Incremental Hierarchical Semantic Scene Graphs with RAG-Style Retrieval"
collection: publications
category: conferences
permalink: /publication/2026-02-07-inherit-sg
excerpt: 'A semantic mapping work; Best Presentation Finalist at the ICRA 2026 Workshop on Robots Meet Prior Maps.'
date: 2026-02-07
venue: 'ICRA 2026 Workshop on Robots Meet Prior Maps (Best Presentation Finalist)'
paperurl: 'https://arxiv.org/abs/2602.12971'
citation: '<b>Yuk Tung Samuel Fang</b>, Zhikang Shi, Jiabin Qiu, Zixuan Chen, Jieqi Shi, Hao Xu, Jing Huo, Yang Gao. (2026). &quot;INHerit-SG: Incremental Hierarchical Semantic Scene Graphs with RAG-Style Retrieval.&quot; <i>ICRA 2026 Workshop on Robots Meet Prior Maps</i>. <b>Best Presentation Finalist</b>.'
image: '/images/inherit_sg_teaser.png'
abstract: 'Driven by advancements in foundation models, semantic scene graphs have emerged as a prominent paradigm for high-level 3D environmental abstraction in robot navigation. However, existing approaches are fundamentally misaligned with the needs of embodied tasks. As they rely on either offline batch processing or implicit feature embeddings, the maps can hardly support interpretable human-intent reasoning in complex environments. To address these limitations, we present INHerit-SG. We redefine the map as a structured, RAG-ready knowledge base where natural-language descriptions are introduced as explicit semantic anchors to better align with human intent. An asynchronous dual-process architecture, together with a Floor-Room-Area-Object hierarchy, decouples geometric segmentation from time-consuming semantic reasoning. An event-triggered map update mechanism reorganizes the graph only when meaningful semantic events occur. This strategy enables our graph to maintain long-term consistency with relatively low computational overhead. For retrieval, we deploy multi-role Large Language Models (LLMs) to decompose queries into atomic constraints and handle logical negations, and employ a hard-to-soft filtering strategy to ensure robust reasoning. This explicit interpretability improves the success rate and reliability of complex retrievals, enabling the system to adapt to a broader spectrum of human interaction tasks. We evaluate INHerit-SG on a newly constructed dataset, HM3DSem-SQR, and in real-world environments. Experiments demonstrate that our system achieves state-of-the-art performance on complex queries, and reveal its scalability for downstream navigation tasks.'
---
<p style="margin-bottom: 20px;">
  <span style="display: inline-block; background-color: #b8860b; color: #fff; padding: 4px 12px; border-radius: 4px; font-weight: bold; font-size: 0.9em;">🏆 Best Presentation Finalist — ICRA 2026 Workshop on Robots Meet Prior Maps</span>
</p>

This paper presents INHerit-SG, an incremental hierarchical semantic scene graph generation method with RAG-style retrieval capabilities.

<!-- ============================================================
     Real-Robot Demos
     Drop your demo files into:  /images/demos/inherit-sg/
     Supported: .mp4, .webm (video) and .gif, .png, .jpg (image)
     Anything you add there shows up here automatically — no code edits needed.
     ============================================================ -->
{% assign demo_files = site.static_files | where_exp: "f", "f.path contains '/images/demos/inherit-sg/'" | sort: "path" %}
{% if demo_files.size > 0 %}
<div style="margin-top: 30px;">
  <h2 id="real-robot-demos">Real-Robot Demos</h2>
  <p style="color: #666;">Captured on a real robot during deployment and data collection.</p>
  {% for f in demo_files %}
    {% assign ext = f.extname | downcase %}
    {% if ext == '.mp4' or ext == '.webm' %}
      <div style="margin-bottom: 20px; text-align: center;">
        <video controls loop muted playsinline style="max-width: 100%; border-radius: 5px; border: 1px solid #ddd;">
          <source src="{{ f.path }}" type="video/{{ ext | remove: '.' }}">
          Your browser does not support the video tag.
        </video>
      </div>
    {% elsif ext == '.gif' or ext == '.png' or ext == '.jpg' or ext == '.jpeg' %}
      <div style="margin-bottom: 20px; text-align: center;">
        <img src="{{ f.path }}" alt="INHerit-SG demo" style="max-width: 100%; border-radius: 5px; border: 1px solid #ddd;">
      </div>
    {% endif %}
  {% endfor %}
</div>
{% endif %}
