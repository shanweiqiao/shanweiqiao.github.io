---
title: "Enhancing Speech Large Language Models with Prompt-Aware Mixture of Audio Encoders"
collection: publications
category: conferences
permalink: /publication/EMNLP_25_AMoE
excerpt: 'We propose Prompt-aware Mixture (PaM) to enhance the Speech LLM that uses multiple audio encoders.'
date: 2025-09-17
venue: 'EMNLP'
slidesurl: 'https://shanweiqiao.github.io/files/EMNLP2025-Slides.pdf'
paperurl: 'https://shanweiqiao.github.io/files/EMNLP_25_AMoE.pdf'
citation: '**Shan W**, Li Y, Zhang Y, et al. Enhancing Speech Large Language Models with Prompt-Aware Mixture of Audio Encoders[J]. arXiv preprint arXiv:2502.15178, 2025.'
---

Connecting audio encoders with large language models (LLMs) allows the LLM to perform various audio understanding tasks, such as automatic speech recognition (ASR) and audio captioning (AC). Most research focuses on training an adapter layer to generate a unified audio feature for the LLM. However, different tasks may require distinct features that emphasize either semantic or acoustic aspects, making task-specific audio features more desirable. In this paper, we propose Prompt-aware Mixture (PaM) to enhance the Speech LLM that uses multiple audio encoders. Our approach involves using different experts to extract different features based on the prompt that indicates different tasks. Experiments demonstrate that with PaM, only one Speech LLM surpasses the best performances achieved by all single-encoder Speech LLMs on ASR, Speaker Number Verification, and AC tasks. PaM also outperforms other feature fusion baselines, such as concatenation and averaging.