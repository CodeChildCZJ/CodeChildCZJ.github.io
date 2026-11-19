---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hi! I'm **Chen Zengjie (陈增杰)**, a Master's student at the [School of Software Engineering, Zhejiang University](https://www.sse.zju.edu.cn/). My research focuses on **multimodal large language models**, **embodied intelligence**, **reinforcement learning**, and **self-evolving agents**.

## Research Interests

- Efficient MLLMs: visual token reduction
- Embodied agents: tool-using agents, self-evolving skills, memory and tools
- Reinforcement learning for agents and robot policies

## Publications

- **Accelerating Multimodal Large Language Models with Prior-Corrected Token Reduction** (PriorTR)  
  **Zengjie Chen**, Yuxiang Cai, Jingcai Guo, Taotao Cai, Jianwei Yin, Zhi Chen  
  *ECCV 2026* (first author) · [[Paper]](https://arxiv.org/abs/2606.24156) [[Code]](https://github.com/CodeChildCZJ/PriorTR)

## Projects

- **Loom: A Self-Evolving Embodied Agent for Long-Horizon Robot Manipulation** (2026.06 – Present)  
  Loom is an embodied agent built on a frozen vision-language model. It calls tools (a VLA policy, arm and gripper motion control, perception) and pre-registered skills, and can write Python programs that run in a sandbox. Before each physical action, a guard check decides whether to execute, revise or block it, so completed progress is not undone. Across batches, an LLM diagnoses failed rollouts, revises supervision rules and memory, and creates new skills and tools; each change is verified on the same states before it is promoted. On LIBERO-Pro, self-evolution raises the success rate from 46% to 67%, 10.6% above Harness VLA with the same planner.

## Competitions & Awards

- [2024.12] **Silver Medal**, 49th ICPC Asia Regional Contest (Kunming)
- [2024.11] **Gold Medal**, 49th ICPC Asia Regional Contest (Nanjing)
- [2024.11] **Silver Medal**, 10th CCPC China Collegiate Programming Contest (Zhengzhou)
- [2024.10] **Silver Medal**, 10th CCPC China Collegiate Programming Contest (Harbin)

## Education

- **M.S.** in Software Engineering, Zhejiang University, 2025 – Present
- **B.S.** in Artificial Intelligence (人工智能), Northeastern University (东北大学), 2021 – 2025

## Contact

- Email: [codechild@zju.edu.cn](mailto:codechild@zju.edu.cn)
- GitHub: [CodeChildCZJ](https://github.com/CodeChildCZJ)
