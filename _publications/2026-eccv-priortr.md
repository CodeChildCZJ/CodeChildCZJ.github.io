---
title: "Accelerating Multimodal Large Language Models with Prior-Corrected Token Reduction"
collection: publications
category: conferences
permalink: /publication/2026-eccv-priortr
excerpt: "A training-free visual token reduction method that separates task-conditioned attention from the model-induced prior, estimated in a single forward pass with a null token."
date: 2026-06-01
venue: "European Conference on Computer Vision (ECCV), 2026"
paperurl: "https://arxiv.org/abs/2606.24156"
codeurl: "https://github.com/CodeChildCZJ/PriorTR"
citation: "<b>Zengjie Chen</b>, Yuxiang Cai, Jingcai Guo, Taotao Cai, Jianwei Yin, Zhi Chen. &quot;Accelerating Multimodal Large Language Models with Prior-Corrected Token Reduction.&quot; <i>ECCV</i>, 2026."
---

Many visual token reduction methods rank tokens by text-visual attention, but attention is often dominated by a model-induced prior that favors task-agnostic regions, which suppresses instruction-relevant tokens. **PriorTR** is a training-free method that estimates this prior with a null token inside the same attention block, contrasts it with the task-conditioned attention, and keeps the tokens that add the most usable information. It improves the accuracy-efficiency trade-off over strong training-free baselines, especially under aggressive token budgets (e.g., retaining 94.5% of the average performance of LLaVA-1.5-7B with only 11.1% of the visual tokens).

[[Paper (arXiv)]](https://arxiv.org/abs/2606.24156) [[Code]](https://github.com/CodeChildCZJ/PriorTR)
