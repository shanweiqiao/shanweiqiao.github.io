---
title: "The NiuTrans Machine Translation Systems for WMT20"
collection: publications
category: manuscripts
permalink: /publication/WMT20
excerpt: 'WMT20 Rank first in Japanese↔English both side.'
date: 2022-06-01
venue: 'Workshop'
slidesurl: 
paperurl: 'https://shanweiqiao.github.io/files/WMT20.pdf'
citation: 'Zhang Y, Wang Z, Cao R, et al. The niutrans machine translation systems for wmt20[C]//Proceedings of the Fifth Conference on Machine Translation. 2020: 338-345.'
---

This paper describes NiuTrans neural machine translation systems of the WMT20 news translation tasks. We participated in Japanese↔English, English→Chinese, Inuktitut→English and Tamil→English total five tasks and rank first in Japanese↔English both sides. We mainly utilized iterative backtranslation, different depth and widen model architectures, iterative knowledge distillation and iterative fine-tuning. And we find that adequately widened and deepened the model simultaneously, the performance will significantly improve. Also, iterative fine-tuning strategy we implemented is effective during adapting domain. For Inuktitut→English and Tamil→English tasks, we built multilingual models separately and employed pretraining word embedding to obtain better performance.