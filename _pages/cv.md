---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}
<a href="../my_CV.pdf" target="_blank">Download CV (PDF)</a>

**Yuk Tung Samuel Fang**  
Also published as: **Yudong Fang**  
Nanjing University (Suzhou Campus) | Hong Kong SAR | B.Sc. Intelligent Science and Technology (Exp. 2027)  
[Website](https://fangyuktung.github.io/) | [Email](mailto:231880023@smail.nju.edu.cn)

## Research Interests
* Robotics; perception and inference for embodied systems. Recent experience in navigation and semantic mapping; actively exploring broader directions. Seeking opportunities for overseas graduate studies (Fall 2027 entry).

## Education
* **Nanjing University (Suzhou Campus)**, Suzhou, China
    * B.Sc. Intelligent Science and Technology (Expected 2027)
    * **GPA:** 4.44 / 5.00
    * **Selected coursework (scores):** Database Systems (96), Operating Systems (95), Data Structures & Algorithms (95), Machine Learning (94), Deep Learning (94), Programming Practicum (94.9)

## Research Experience
**Undergraduate Researcher** (2025--present)  
*Inference & Learning Research Group (led by Prof. Yang Gao), State Key Laboratory for Novel Software Technology, Nanjing University*  
* Supervised by tenure-track AP Prof. Jieqi Shi, who provided guidance on research design, paper writing, and project execution; collaborated closely on prototyping, integration, and manuscript preparation.

**Zero-Shot Vision-and-Language Navigation (LaViRA)** (2025.05--2025.09)  
* To address the trade-off in zero-shot VLN-CE between environment-specific waypoint predictors and underutilized large model reasoning, we developed a framework for zero-shot VLN-CE. It decomposes actions into language planning, vision grounding, and robot control. This uses MLLMs for better reasoning and generalization. Achieved state-of-the-art results on VLN-CE benchmark and deployed on Unitree Go1 and Agilex Cobot Magic wheeled robot with hardware integration. Accepted at ICRA 2026.

**Active Exploration with Semantic Map Prediction (SEA)** (2025.09--2025.10)  
* To enhance active exploration efficiency by overcoming reliance on one-step waypoint prediction and enabling long-term environmental understanding, we created a method for active exploration using semantic map prediction. It employs an iterative framework with RL policies and uncertainty rewards, which guides the agent to uncertain areas for efficient mapping. Deployed on Unitree Go1 and Agilex Cobot Magic wheeled robot with end-to-end integration. Outperformed baselines in coverage and efficiency.

**Incremental Hierarchical Semantic Scene Graphs (INHerit-SG)** (2025.10--2026.02)  
* To overcome misalignment of existing semantic scene graphs with embodied tasks, which rely on offline processing or implicit embeddings lacking interpretability, we developed an online semantic scene graph system with a multi-hierarchy and RAG-style retrieval. It uses asynchronous dual-process updates and event triggers for efficiency. This supports interpretable, human-aligned reasoning in embodied tasks. Achieved state-of-the-art results on HM3DSem-SQR dataset (self-built), human studies, and real-world robot trajectories.

## Publications & Preprints
* **LaViRA: Language-Vision-Robot Actions Translation for Zero-Shot Vision Language Navigation in Continuous Environments**  
    * H. Ding, Z. Xu, **Y. Fang (Yudong)**, Y. Wu, Z. Chen, J. Shi, J. Huo, Y. Zhang, Y. Gao  
    * *ICRA 2026*. [arXiv:2510.19655](https://arxiv.org/abs/2510.19655) | [Project Page](https://robo-lavira.github.io/lavira-zs-vln/)  
    * *Contribution:* Led real-robot deployment (on Unitree Go1) and system integration. (2025.05 -- 2025.09)

* **SEA: Semantic Map Prediction for Active Exploration of Uncertain Areas**  
    * H. Ding, X. Liang, **Y. Fang (Yudong)**, Y. Wu, J. Shi, J. Huo, W. Li, J. Wu, Y.-K. Lai, Y. Gao  
    * *Under review*. [arXiv:2510.19766](https://arxiv.org/abs/2510.19766) | [Project Page](https://robo-lavira.github.io/sea-active-exp/)  
    * *Contribution:* Led real-robot deployment (on Unitree Go1) and end-to-end integration for on-robot execution. (2025.09 -- 2025.10)

* **INHerit-SG: Incremental Hierarchical Semantic Scene Graphs with RAG-Style Retrieval**  
    * **Y.T.S. Fang**, Z. Shi, J. Qiu, Z. Chen, J. Shi, H. Xu, J. Huo, Y. Gao  
    * *Under review*. [arXiv:2602.12971](https://arxiv.org/abs/2602.12971) | [Project Page](https://fangyuktung.github.io/INHeritSG.github.io/)  
    * *Contribution:* Independent first author; led whole end-to-end pipeline, paper writing, figures/tables, experiment design, visualization, supplement, hardware/communication bring-up, and real-robot data collection. (2025.10 -- 2026.02)

## Honors & Awards
* NJU Scholarship for HK/Macao & Overseas Chinese Students --- **First Prize** (Sophomore year; university-wide; 5 awardees; defense required)
* NJU Scholarship for HK/Macao & Overseas Chinese Students --- **Third Prize** (Freshman year; university-wide)

## Skills
* **Programming:** Python (for ML pipelines and ROS integration), C++
* **Robotics:** ROS (for data collection across diverse sensors, inter-device communication in complex setups, downstream control via SDKs for dynamic motion planning and execution), real-robot deployment and debugging
* **Tools:** Linux, Git; proficient with AI-assisted coding tools (for rapid prototyping, debugging, and iterative development)
* **Hardware:** 3D modeling & printing (custom fixtures for sensor integration); sensor/compute configurations (possess hands-on experience with various commonly used robot cameras)
