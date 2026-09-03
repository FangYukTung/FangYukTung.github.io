---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an undergraduate student majoring in Intelligence Science and Technology at Nanjing University. I come from Hong Kong and am currently seeking opportunities for overseas graduate studies (Fall 2027 entry).

My research focuses on embodied AI and robotics, particularly how robots build, maintain, and use **3D structured scene representations** of changing environments. I am interested in persistent embodied memory and its role in supporting reliable long-horizon navigation and manipulation under partial observability.

I am currently an undergraduate researcher working with Prof. [Jieqi Shi](https://jayceeshi.github.io/) in the **Inference and Learning Research Group**, led by Prof. [Yang Gao](https://cs.nju.edu.cn/gaoyang/) at the **State Key Laboratory for Novel Software Technology**, Nanjing University. I will soon join **Mondo Robotics** as a Research Intern under the supervision of [Prof. Hao Xu](https://www.xuhao1.me/).

## News

- **[2026.09]** Will soon join **Mondo Robotics** as a Research Intern under the supervision of [Prof. Hao Xu](https://www.xuhao1.me/).
- **[2026.07]** Joined the **LINS Lab at NUS** as an onsite Summer Research Intern with [Prof. Lin Shao](https://linsats.github.io/), working on life-long mobile manipulation and embodied memory evaluation.
- **[2026.06]** Invited to serve as a **Reviewer for IEEE Robotics and Automation Letters (RA-L)**.
- **[2026.06]** **INHerit-SG** named a **Best Presentation Finalist** at the ICRA 2026 Workshop on Robots Meet Prior Maps.
- **[2026.05]** **INHerit-SG** selected for **Oral Presentation** at the ICRA 2026 Workshop on Robots Meet Prior Maps.
- **[2026.01]** **LaViRA** accepted to **ICRA 2026**.

## Publications

<div style="display: flex; gap: 20px; margin-bottom: 20px;">
  <div style="flex: 0 0 30%;">
    <img src="/images/inherit_sg_teaser.png" alt="INHerit-SG Teaser" style="width: 100%; border-radius: 5px; border: 1px solid #ddd;">
  </div>
  <div style="flex: 1;">
    <a href="/publication/2026-02-07-inherit-sg" style="text-decoration: none;">
      <h3 style="margin-top: 0; color: #0056b3;">INHerit-SG: Incremental Hierarchical Semantic Scene Graphs with RAG-Style Retrieval</h3>
    </a>
    <p style="margin-bottom: 5px;">
      <strong>Yuk Tung Samuel Fang</strong>, Zhikang Shi, Jiabin Qiu, Zixuan Chen, Jieqi Shi, Hao Xu, Jing Huo, Yang Gao
    </p>
    <p style="font-style: italic; color: #666; margin-bottom: 5px;">
      ICRA 2026 Workshop on Robots Meet Prior Maps (Oral)
      <span style="display: inline-block; background-color: #b8860b; color: #fff; padding: 1px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; font-style: normal;">🏆 Best Presentation Finalist</span>
    </p>
    <p style="margin-bottom: 0;">
      <a href="https://arxiv.org/abs/2602.12971" target="_blank">[arXiv]</a>
      <a href="https://fangyuktung.github.io/INHeritSG.github.io/" target="_blank">[Project Page]</a>
      <a href="/publication/2026-02-07-inherit-sg#real-robot-demos">[Real-Robot Demos]</a>
    </p>
  </div>
</div>

<div style="display: flex; gap: 20px; margin-bottom: 20px;">
  <div style="flex: 0 0 30%;">
    <img src="/images/lavira_teaser.png" alt="LaViRA Teaser" style="width: 100%; border-radius: 5px; border: 1px solid #ddd;">
  </div>
  <div style="flex: 1;">
    <a href="/publication/2025-09-16-lavira" style="text-decoration: none;">
      <h3 style="margin-top: 0; color: #0056b3;">LaViRA: Language-Vision-Robot Actions Translation for Zero-Shot Vision Language Navigation in Continuous Environments</h3>
    </a>
    <p style="margin-bottom: 5px;">
      Hongyu Ding, Ziming Xu, <strong>Yudong Fang</strong>, You Wu, Zixuan Chen, Jieqi Shi, Jing Huo, Yang Gao
    </p>
    <p style="font-style: italic; color: #666; margin-bottom: 5px;">
      IEEE International Conference on Robotics and Automation <span class="demo-tag blue" style="font-style: normal;">ICRA 2026</span>
    </p>
    <p style="margin-bottom: 0;">
      <a href="https://arxiv.org/abs/2510.19655" target="_blank">[arXiv]</a>
      <a href="https://robo-lavira.github.io/lavira-zs-vln/" target="_blank">[Project Page]</a>
      <a href="/publication/2025-09-16-lavira#real-robot-demos">[Real-Robot Demos]</a>
    </p>
  </div>
</div>

## Real-Robot Demos

<p style="color: #555; margin-top: -6px;">Clips from my own deployments on <strong>real robots</strong> — not simulation. Unmute in the player for sound.</p>

<style>
.demo-reel { display: flex; flex-wrap: wrap; gap: 20px; margin: 12px 0 10px; }
.demo-card { flex: 1 1 320px; min-width: 280px; }
.demo-card video { width: 100%; aspect-ratio: 16 / 9; object-fit: cover; background: #000; border-radius: 8px; border: 1px solid #ddd; display: block; box-shadow: 0 2px 8px rgba(0,0,0,0.10); transition: transform .2s ease, box-shadow .2s ease; }
.demo-card video:hover { transform: translateY(-3px); box-shadow: 0 8px 20px rgba(0,0,0,0.18); }
.demo-cap { margin: 10px 0 0; line-height: 1.4; }
.demo-cap a { color: #0056b3; font-weight: 600; text-decoration: none; }
.demo-cap a:hover { text-decoration: underline; }
.demo-tag { display: inline-block; color: #fff; padding: 1px 8px; border-radius: 4px; font-weight: bold; font-size: 0.78em; vertical-align: middle; }
.demo-tag.gold { background: #b8860b; }
.demo-tag.blue { background: #0056b3; }
.demo-sub { color: #666; font-size: 0.9em; }
</style>

<div class="demo-reel">
  <div class="demo-card">
    <video autoplay loop muted playsinline controls preload="metadata">
      <source src="/images/demos/inherit-sg/inheritsg_demo.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p class="demo-cap">
      <a href="/publication/2026-02-07-inherit-sg">INHerit-SG</a>
      <span class="demo-tag gold">🏆 Oral · Best Presentation Finalist</span><br>
      <span class="demo-sub">Hierarchical semantic scene graphs · led real-robot data collection</span>
    </p>
  </div>
  <div class="demo-card">
    <video autoplay loop muted playsinline controls preload="metadata">
      <source src="/images/demos/lavira/dog2.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p class="demo-cap">
      <a href="/publication/2025-09-16-lavira">LaViRA</a>
      <span class="demo-tag blue">ICRA 2026</span><br>
      <span class="demo-sub">Zero-shot vision-language navigation · led Unitree Go1 deployment</span>
    </p>
  </div>
</div>

## CV

You can download my full CV here: [Download CV (PDF)](my_CV.pdf)
