---
title: "Early exit is a natural capability in transformer-based models: An empirical study on early exit without joint optimization"
collection: publications
category: conferences
permalink: /publication/Arxiv_23_early_exit_capability
excerpt: 'We explore the possibility of LLMs EE without additional output layers and joint optimization.'
date: 2023-09-17
venue: 'Arxiv'
paperurl: 'https://shanweiqiao.github.io/files/Arxiv_23_early_exit_capability.pdf'
citation: 'Shan W, Meng L, Zheng T, et al. Early exit is a natural capability in transformer-based models: An empirical study on early exit without joint optimization[J]. arXiv preprint arXiv:2412.01455, 2024.'
---

Large language models (LLMs) exhibit exceptional performance across various downstream tasks. However, they encounter limitations due to slow inference speeds stemming from their extensive parameters. The early exit (EE) is an approach that aims to accelerate auto-regressive decoding. EE generates outputs from intermediate layers instead of using the whole model, which offers a promising solution to this challenge. However, additional output layers and joint optimization used in conventional EE hinder the application of EE in LLMs. In this paper, we explore the possibility of LLMs EE without additional output layers and joint optimization. Our findings indicate that EE is a natural capability within transformerbased models. While joint optimization does not give model EE capability, it must be employed to address challenges by improving the accuracy of locating the optimal EE layer through gating functions. Additionally, our study reveals patterns in EE behavior from a sub-word perspective based on the LLaMA model and the potential possibility for EE based on sub-layers.