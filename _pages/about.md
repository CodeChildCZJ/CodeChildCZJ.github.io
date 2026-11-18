---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hi! I'm **Chen Zengjie (陈增杰)**, a Master's student at the [School of Software Engineering, Zhejiang University](https://www.sse.zju.edu.cn/), working in the "Physical Intelligence" group of the ACES Lab. My research focuses on **multimodal large language models**, **embodied intelligence**, **reinforcement learning**, and **self-evolving agents**.

## Research Interests

- Efficient MLLMs: visual token reduction, inference acceleration
- Embodied agents: LLM planners driving VLA policies, self-evolving skills, memory and tools
- RL post-training for multimodal agents: multi-turn agentic RL, GRPO/PPO

## Publications

- **Accelerating Multimodal Large Language Models with Prior-Corrected Token Reduction** (PriorTR)  
  **Zengjie Chen**, Yuxiang Cai, Jingcai Guo, Taotao Cai, Jianwei Yin, Zhi Chen  
  *ECCV 2026* (first author) · [[Paper]](https://arxiv.org/abs/2606.24156) [[Code]](https://github.com/CodeChildCZJ/PriorTR)

## Projects

- **Loom: A Self-Evolving Embodied Agent for Long-Horizon Robot Manipulation** (2026.06 – Present)  
  With the LLM planner and the VLA policy frozen, Loom adds an execution-supervision layer that tracks task progress and decides whether each action should run, be revised, or be blocked. The agent evolves its supervision rules, skills, memory and tools from failed rollouts, and each change is verified against the previous version before it is promoted. On LIBERO-Pro, self-evolution raises the success rate from 46% to 67%, 10.6% above Harness VLA with the same planner.
- **VimPro: Hierarchical Memory and Evidence Selection for Long-Video Agents** (2025.12 – 2026.08)  
  A long-video agent with episodic, evidence and working memory. A lightweight proxy model, MemLens, trained with SFT + GRPO, selects answer-relevant evidence for the answering agent. It reaches 81.0 / 73.4 / 74.7 on Video-MME / LongVideoBench / LVBench while cutting inference time by 64.1% and token usage by 73.6%.
- **Multimodal Agentic RL Framework on verl** (2025.06 – 2025.09)  
  Extended verl from single-turn generation to asynchronous multi-turn agent-environment interaction with tool calling, interleaved image/text trajectories (M-RoPE aligned), GRPO with loss masking over environment tokens, and rewards combining task correctness, tool validity and LLM-as-a-Judge.

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
