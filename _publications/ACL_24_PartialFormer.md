---
title: "Co-author: PartialFormer: Modeling Part Instead of Whole for Machine Translation"
collection: publications
category: conferences
permalink: /publication/ACL_24_PartialFormer
excerpt: 'We introduce PartialFormer, a parameter-efficient Transformer architecture utilizing multiple smaller FFNs to reduce parameters and computation while maintaining essential hidden dimensions.'
date: 2025-09-17
venue: 'EMNLP'
paperurl: 'https://shanweiqiao.github.io/files/ACL_24_PartialFormer.pdf'
citation: 'Zhang Y, Ma X, Kou K, et al. Leveraging Unit Language Guidance to Advance Speech Modeling in Textless Speech-to-Speech Translation[J]. arXiv preprint arXiv:2505.15333, 2025.'
---

The design choices in Transformer feedforward neural networks have resulted in significant computational and parameter overhead. In this work, we emphasize the importance of hidden dimensions in designing lightweight FFNs, a factor often overlooked in previous architectures. Guided by this principle, we introduce PartialFormer, a parameter-efficient Transformer architecture utilizing multiple smaller FFNs to reduce parameters and computation while maintaining essential hidden dimensions. These smaller FFNs are integrated into a multihead attention mechanism for effective collaboration. We also propose a tailored head scaling strategy to enhance PartialFormer’s capabilities. Furthermore, we present a residual-like attention calculation to improve depth scaling within PartialFormer. Extensive experiments on 9 translation tasks and 1 abstractive summarization task validate the effectiveness of our PartialFormer approach on machine translation and summarization tasks. Our code would be available at: https://github.com/zhengkid/PartialFormer.