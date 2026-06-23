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

## Education

*   **Nanjing University (Suzhou Campus)**, Suzhou, China
    *   B.Sc. Intelligent Science and Technology (Expected 2027)
    *   **GPA:** 4.48 / 5.00
    *   **Selected Coursework:** Data Mining (95), Database Systems (96), Operating Systems (95), Data Structures & Algorithms (95), Machine Learning (94), Deep Learning (94), Programming Practicum (94.9)

## Research Interests

*   Embodied AI and robotics — perception, spatial memory, and decision-making for reliable action in unstructured real-world environments.
*   Hands-on experience spanning navigation, semantic mapping, and real-robot deployment.
*   Seeking opportunities for overseas graduate studies (Fall 2027 entry).

## Publications & Preprints

*   **LaViRA: Language-Vision-Robot Actions Translation for Zero-Shot Vision Language Navigation in Continuous Environments**
    *   H. Ding, Z. Xu, **Y. Fang (Yudong)**, Y. Wu, Z. Chen, J. Shi, J. Huo, Y. Zhang, Y. Gao
    *   *ICRA 2026*. [arXiv:2510.19655](https://arxiv.org/abs/2510.19655) | [Project Page](https://robo-lavira.github.io/lavira-zs-vln/)
    *   *Contribution:* Led real-robot deployment (on Unitree Go1) and system integration.

*   **INHerit-SG: Incremental Hierarchical Semantic Scene Graphs with RAG-Style Retrieval**
    *   **Y.T.S. Fang**, Z. Shi, J. Qiu, Z. Chen, J. Shi, H. Xu, J. Huo, Y. Gao
    *   *ICRA 2026 Workshop on Robots Meet Prior Maps*, **Oral Presentation, Best Presentation Finalist**. [arXiv:2602.12971](https://arxiv.org/abs/2602.12971) | [Project Page](https://fangyuktung.github.io/INHeritSG.github.io/)
    *   *Contribution:* Independent first author; led whole end-to-end pipeline, paper writing, figures/tables, experiment design, visualization, supplement, hardware/communication bring-up, and real-robot data collection.

## Research Experience

**Incoming Research Intern** (Summer 2026)
*National University of Singapore (NUS) — Advisor: Prof. Lin Shao*

*   Incoming summer research in embodied AI.

**Undergraduate Researcher** (2025--present)
*Inference & Learning Research Group (led by Prof. Yang Gao), State Key Laboratory for Novel Software Technology, Nanjing University*

*   Supervised by tenure-track AP Prof. Jieqi Shi, who provided guidance on research design, paper writing, and project execution; collaborated closely on prototyping, integration, and manuscript preparation.

### Zero-Shot Vision-and-Language Navigation (LaViRA) (2025.05 -- 2025.09)
*Advisors: Prof. Jieqi Shi, Prof. Jing Huo*

*   Addressed trade-offs in existing zero-shot VLN-CE methods between scene generalization and MLLM reasoning utilization.
*   Developed a coarse-to-fine hierarchical framework that decomposes actions into language planning for high-level decisions, vision grounding for perceptual integration, and robot control for precise movements.
*   Leveraged varying scales of Multimodal Large Language Models (MLLMs) to enhance reasoning, grounding, and navigation efficiency in unseen environments.
*   Implemented modular decomposition to maintain transparency and support real-world deployment without prior training.
*   Achieved state-of-the-art performance on the VLN-CE benchmark with Success Rate (SR) of 38.3\% and Success weighted by Path Length (SPL) of 28.3\% using Gemini-2.5-Pro, demonstrating superior generalization with +16.1\% SR and +17.7\% SPL over InstructNav; deployed on Unitree Go1 and Agilex Cobot Magic robots. Accepted at ICRA 2026.

### Active Exploration with Semantic Map Prediction (SEA) (2025.09 -- 2025.10)
*Advisors: Prof. Jieqi Shi, Prof. Jing Huo*

*   Tackled limitations in learning-based exploration methods, including the lack of long-term environmental understanding and efficiency in global awareness.
*   Designed an iterative prediction-exploration framework using semantic map prediction to forecast missing areas based on current observations.
*   Incorporated an ASC-based local mapper for predictions and confidence estimation, alongside RL-based hierarchical policies for two-stage navigation.
*   Developed a confidence-aware full mapper to accumulate and adjust local maps, guiding exploration via differences between predicted and actual maps.
*   Deployed and debugged the full pipeline on Habitat datasets, with real-robot integration on Unitree Go1 and Agilex Cobot Magic platforms.

### Incremental Hierarchical Semantic Scene Graphs (INHerit-SG) (2025.10 -- 2026.02)
*Advisors: Prof. Jieqi Shi, Prof. Hao Xu, Prof. Jing Huo*

*   Resolved misalignments in existing semantic scene graphs, including offline processing, lack of interpretability, and flat structures unsuitable for embodied tasks.
*   Constructed a semantic graph evaluation dataset, HM3DSem-SQR, focusing on complex natural language command queries and a human study dataset focusing on semantic accuracy.
*   Introduced an online system with a Floor-Room-Area-Object hierarchy and RAG-style retrieval, using natural-language descriptions as semantic anchors for human-intent alignment.
*   Employed an asynchronous dual-process architecture to decouple geometric segmentation from semantic reasoning, with event-triggered updates for long-term consistency and low overhead.
*   Deployed multi-role Large Language Models (LLMs) to decompose queries into atomic constraints, handle logical negations, and apply hard-to-soft filtering for robust reasoning.
*   Achieved state-of-the-art results on the HM3DSem-SQR dataset with geometric accuracy of 37.7\% (within 1m, +15\% over DualMap) and semantic accuracy of 70.6\%, real-world trajectory evaluations with 60.0\% success rate (+70\% over baselines). The system also demonstrates scalability for downstream navigation tasks.

## Research in Progress

**Lifelong Mobile-Manipulation Memory Benchmark** (2026.03 -- present)

*   Designing a benchmark that evaluates world-model maintenance under continuous household perturbations, organized around a three-level capability framework (build/organize world model, update under conflicts, memory-guided action). Simulation environment implemented; preliminary method under active development.

**Uncertainty-Aware Interactive Object-Goal Navigation** (2026.06 -- present)

*   Developing a decision framework for when an embodied agent should act, explore, or ask the user, based on two-layer uncertainty modeling and information-gain-driven question generation. Research proposal completed; feasibility validated via baseline (SG-Nav, CoIN-Bench) reproduction.

## Honors & Awards

*   **First Prize**, NJU Scholarship for HK/Macao & Overseas Chinese Students (Sophomore year; university-wide; 5 awardees (Top 2%); defense required)
*   **Third Prize**, NJU Scholarship for HK/Macao & Overseas Chinese Students (Freshman year; university-wide)

## Academic Service

*   Reviewer (by invitation), *IEEE Robotics and Automation Letters* (RA-L), 2026

## Skills

*   **Programming:** Python (for ML pipelines and ROS integration), C++
*   **Robotics:** ROS (for data collection across diverse sensors, inter-device communication in complex setups, downstream control via SDKs for dynamic motion planning and execution), real-robot deployment and debugging
*   **Tools:** Linux, Git; agentic coding workflows (Claude Code / Codex) in remote development for rapid prototyping and project automation
*   **Hardware:** 3D modeling & printing (custom fixtures for sensor integration); sensor/compute configurations (possess hands-on experience with various commonly used robot cameras)
