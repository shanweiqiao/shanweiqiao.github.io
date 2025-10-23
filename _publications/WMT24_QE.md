---
title: "HW-TSC 2024 Submission for the Quality Estimation Shared Task"
collection: publications
category: manuscripts
permalink: /publication/WMT24_QE
excerpt: 'This paper focuses on Huawei Translation Services Center’s (HW-TSC’s) submission to the sentence-level QE shared task.'
date: 2024-08-01
venue: 'Workshop'
slidesurl: 
paperurl: 'https://shanweiqiao.github.io/files/WMT24_QE.pdf'
citation: 'Shan W, Zhu M, Li Y, et al. HW-TSC 2024 Submission for the Quality Estimation Shared Task[C]//Proceedings of the Ninth Conference on Machine Translation. 2024: 535-540.'
---

Quality estimation (QE) is a crucial technique for evaluating the quality of machine translations without the need for reference translations. This paper focuses on Huawei Translation Services Center’s (HW-TSC’s) submission to the sentence-level QE shared task, named LLMsenhanced-CrossQE. Our system builds upon the CrossQE architecture from our submission from last year, which consists of a multilingual base model and a task-specific downstream layer. The model input is a concatenation of the source and the translated sentences. To enhance performance, we fine-tuned and ensembled multiple base models, including XLM-R, InfoXLM, RemBERT, and CometKiwi. Specifically, we employed two pseudo-data generation methods: 1) a diverse pseudo-data generation method based on the corruption-based data augmentation technique introduced last year, and 2) a pseudo-data generation method that simulates machine translation errors using large language models (LLMs). Our results demonstrate that the system achieves outstanding performance on sentence-level QE test sets.
