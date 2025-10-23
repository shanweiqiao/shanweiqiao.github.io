---
title: "A Survey on Conditional Computation"
collection: publications
category: conferences
permalink: /publication/Arxiv_23_conditional_computation_survey
excerpt: 'Survey on research about early exit and mixture of expert.'
date: 2023-09-17
venue: 'Arxiv'
paperurl: 'https://shanweiqiao.github.io/files/Arxiv_23_conditional_computation_survey.pdf'
citation: 'Shan W, et al. A Survey on Conditional Computation[J]. 2023.'
---

Using large-scale models has proven to be an effective approach to enhancing model performance and enabling various applications. However, such models come at a significant computation cost. To address this issue, conditional computation has been proposed to dynamically adjust the model scale based on input via dynamic dropout and an additional gate network. The gate network partitions the original network (called backbone network) into multiple sub-networks and selects a specific sub-network for each input. In this paper, we present a novel classification not from model structure to discuss the sub-network granularity and the training methods of this framework from a new perspective, namely the definition and learning of decision sequence respectively, and summarize the latest approaches in conditional computation.