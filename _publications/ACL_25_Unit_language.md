---
title: "[Co-author] Leveraging Unit Language Guidance to Advance Speech Modeling in Textless Speech-to-Speech Translation"
collection: publications
category: conferences
permalink: /publication/ACL_25_Unit_language
excerpt: 'We propose the unit language to overcome the two modeling challenges. The unit language can be considered a text-like representation format, constructed using n-gram language modeling.'
date: 2025-09-17
venue: 'ACL 2025 Fingdings'
paperurl: 'https://shanweiqiao.github.io/files/ACL_25_Unit_language.pdf'
citation: 'Zhang Y, Ma X, Kou K, et al. Leveraging Unit Language Guidance to Advance Speech Modeling in Textless Speech-to-Speech Translation[J]. arXiv preprint arXiv:2505.15333, 2025.'
---

The success of building textless speech-tospeech translation (S2ST) models has attracted much attention. However, S2ST still faces two main challenges: 1) extracting linguistic features for various speech signals, called crossmodal (CM), and 2) learning alignment of difference languages in long sequences, called cross-lingual (CL). We propose the unit language to overcome the two modeling challenges. The unit language can be considered a text-like representation format, constructed using n-gram language modeling. We implement multi-task learning to utilize the unit language in guiding the speech modeling process. Our initial results reveal a conflict when applying source and target unit languages simultaneously. We propose task prompt modeling to mitigate this conflict. We conduct experiments on four languages of the Voxpupil dataset. Our method demonstrates significant improvements over a strong baseline and achieves performance comparable to models trained with text.