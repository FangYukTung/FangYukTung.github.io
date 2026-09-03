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

*   **Nanjing University**, Suzhou, China
    *   B.Sc. in Intelligence Science and Technology (Expected Jun. 2027)
    *   **GPA:** 4.48 / 5.00
    *   **Selected Coursework:** Database (96), Data Structures and Algorithms (95), Data Mining (95), Operating Systems (95), Programming Training (94.9), Machine Learning (94), Deep Learning (94)

## Research Interests

*   Embodied AI and robotics, particularly semantic and spatial environment representations, persistent embodied memory, and long-horizon reasoning and planning for navigation and manipulation in partially observable, dynamic environments.

## Publications

*   **INHerit-SG: Incremental Hierarchical Semantic Scene Graphs with RAG-Style Retrieval**
    *   **Y.T.S. Fang**, Z. Shi, J. Qiu, Z. Chen, J. Shi, H. Xu, J. Huo, Y. Gao
    *   *ICRA 2026 Workshop on Robots Meet Prior Maps*; **Oral Presentation; Best Presentation Finalist**. [arXiv](https://arxiv.org/abs/2602.12971) · [Project](https://fangyuktung.github.io/INHeritSG.github.io/)
    *   *Role:* First author and project lead.

*   **LaViRA: Language-Vision-Robot Actions Translation for Zero-Shot Vision-Language Navigation in Continuous Environments**
    *   H. Ding, Z. Xu, **Y.T.S. Fang**, Y. Wu, Z. Chen, J. Shi, J. Huo, Y. Zhang, Y. Gao
    *   *IEEE International Conference on Robotics and Automation (ICRA)*, 2026. [arXiv](https://arxiv.org/abs/2510.19655) · [Project](https://robo-lavira.github.io/lavira-zs-vln/)
    *   *Role:* Implemented the Unitree Go1 real-robot setup and deployment; built an exploratory RAG prototype and contributed to visualization.

## Research Experience

### Incremental Hierarchical Semantic Scene Graphs (INHerit-SG)
**Oct. 2025--Jul. 2026**<br>
*Inference and Learning Research Group, Nanjing University*<br>
*Advised by Prof. Jieqi Shi, Prof. Hao Xu, and Prof. Jing Huo*

*   Developed an incremental semantic scene representation organized as a Floor-Room-Area-Object hierarchy, with an asynchronous dual-process architecture that decouples geometric mapping from semantic reasoning.
*   Designed and refined a query-conditioned retrieval pipeline combining typed constraint parsing, hard-to-soft candidate filtering, relational graph reasoning, and selective visual reranking for compositional and ambiguous language queries.
*   Built HM3DSem-SQR, an evaluation set spanning 36 scenes and 6,084 complex object-retrieval queries involving hierarchy, attributes, relations, and negation; validated the system through simulated, real-world, and human studies, achieving state-of-the-art results with 37.7% retrieval success within 1 m, 70.6% semantic accuracy, and 60.0% success on real-world trajectory evaluation.
*   Following the workshop version, used controlled ablations to test whether richer hierarchy and more complex LLM modules genuinely improved retrieval. Structured interfaces improved smaller local LLMs by 13.54 percentage points but offered little benefit to strong hosted models, while one stronger LLM parser and fail-open reranking proved more reliable than multi-agent parsing and strict visual verification.
*   Based on these findings, redesigned the pipeline around query-conditioned structured retrieval for candidate recall and selective visual reranking for ambiguity resolution. On Main-864, a category-balanced 864-query subset evaluated by strict object identity, achieved 33.56% Strict Top-1, 62.27% Recall@5, and 37.62% SR@1m, with the best or tied-best result across all six query categories.
*   Demonstrated external generalization on the ViGiL3D ScanNet predicted-box protocol, achieving 20.84/18.33 F1@0.25/0.50 for zero-shot grounding with shared ScanNet-supervised Mask3D proposals, 5.14/5.13 percentage points above the best reported trained method.

### Life-Long Mobile Manipulation and Embodied Memory Evaluation
**Mar. 2026--Present**<br>
*Nanjing University; Summer Intern at LINS Lab, National University of Singapore (Jul.--Aug. 2026)*<br>
*Advised by Prof. Jieqi Shi and Prof. Lin Shao*

*   Built a long-horizon mobile-manipulation and environment-perturbation platform in Habitat/ReplicaCAD and AI2-THOR/ProcTHOR, alternating task execution and memory updates under object relocation, hiding, state changes, disappearance, and spawning. Implemented adapters for DovSG, MoMaStage, ConceptGraphs, MomaGraph, and HOV-SG, and stress-tested 50-round sequences in 10 layouts with 822 logged changes.
*   Analysis of these long-horizon runs motivated a three-level controlled diagnostic benchmark that isolates memory-specific capabilities from downstream planning and execution. L1 isolates memory organization and retrieval; L2 frames memory maintenance as belief-state estimation under partial observability, separating observed state updates from uncertainty over unobserved environmental changes and evaluating when new observations are required; L3 tests whether memory improves action under a fixed low-level perception and action-execution pipeline.
*   Built a benchmark with 2,966 retrieval questions, 2,646 update and decision plans, and 108 multi-goal manipulation tasks. On 272 L1 queries, DynaMem and Embodied VideoAgent achieved 81.2% and 91.2% retrieval accuracy. In L2, DynaMem achieved 75.0% and 83.3% accuracy when writing back self-caused changes and incorporating re-observed external changes. In paired L3 tests that changed only the memory input, correct memory increased mean per-task goal completion from 3.3% to 10.6%.

### Zero-Shot Vision-Language Navigation (LaViRA)
**May 2025--Sep. 2025**<br>
*Inference and Learning Research Group, Nanjing University*<br>
*Advised by Prof. Jieqi Shi and Prof. Jing Huo*

*   Built a reusable Unitree Go1 real-robot experimentation platform and adapted LaViRA to it, including communication and sensor integration, navigation execution, deployment, and debugging.
*   Built and tested an exploratory retrieval-augmented generation (RAG) prototype and contributed to visualization of experiments and results.
*   Contributed to the system achieving 38.3% Success Rate and 28.3% SPL on VLN-CE, outperforming InstructNav by 16.1 and 17.9 percentage points, respectively.

### Active Exploration with Semantic Map Prediction (SEA)
**Sep. 2025--Oct. 2025**<br>
*Inference and Learning Research Group, Nanjing University*<br>
*Advised by Prof. Jieqi Shi and Prof. Jing Huo*

*   Explored active navigation using semantic map prediction to infer unobserved regions and guide subsequent exploration.
*   Adapted SEA to the reusable Unitree Go1 real-robot platform developed during LaViRA, and conducted system integration, interface debugging, deployment, and real-robot experiments.

## Honors and Awards

*   **First Prize**, NJU Scholarship for Hong Kong, Macao, and Overseas Chinese Students, Sophomore Year; **5 recipients university-wide**
*   **Third Prize**, NJU Scholarship for Hong Kong, Macao, and Overseas Chinese Students, Freshman Year

## Academic Service

*   Invited Reviewer, *IEEE Robotics and Automation Letters (RA-L)*, 2026

## Technical Skills

*   **Programming and Tools:** Python, C++, Linux, Git
*   **Robotics and Simulation:** ROS, Habitat, AI2-THOR, ProcTHOR, navigation system integration, real-robot deployment and debugging
*   **Embodied AI:** Multimodal model integration, semantic mapping, scene graphs, retrieval-augmented systems
*   **Hardware:** Unitree Go1, RGB-D cameras, 3D modeling and printing
