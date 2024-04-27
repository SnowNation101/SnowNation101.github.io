---
title: "INTERS: Unlocking the Power of Large Language Models in Search with Instruction Tuning"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Instruction tuning dataset for IR'
date: 2024-02-19
venue: 'arXiv'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Yutao Zhu, Peitian Zhang, Chenghao Zhang, Yifei Chen, Binyu Xie, Zhicheng Dou, Zheng Liu, Ji-Rong Wen: INTERS: Unlocking the Power of Large Language Models in Search with Instruction Tuning. CoRR abs/2401.06532 (2024)'
---

Large language models (LLMs) have demonstrated impressive capabilities in various natural language processing tasks. Despite this, their application to information retrieval (IR) tasks is still challenging due to the infrequent occurrence of many IR-specific concepts in natural language. While prompt-based methods can provide task descriptions to LLMs, they often fall short in facilitating a comprehensive understanding and execution of IR tasks, thereby limiting LLMs' applicability. 

To address this gap, in this work, we explore the potential of instruction tuning to enhance LLMs' proficiency in IR tasks. We introduce a novel instruction tuning dataset, INTERS, encompassing 20 tasks across three fundamental IR categories: query understanding, document understanding, and query-document relationship understanding. The data are derived from 43 distinct datasets with manually written templates. Our empirical results reveal that INTERS significantly boosts the performance of various publicly available LLMs, such as LLaMA, Mistral, and Phi, in IR tasks. Furthermore, we conduct extensive experiments to analyze the effects of instruction design, template diversity, few-shot demonstrations, and the volume of instructions on performance. We make our dataset and the fine-tuned models publicly accessible at [THIS URL](https://github.com/DaoD/INTERS).
