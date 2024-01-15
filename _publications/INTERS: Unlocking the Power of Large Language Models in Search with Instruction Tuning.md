---
title: "INTERS: Unlocking the Power of Large Language Models in Search with Instruction Tuning"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-01-15
venue: 'Journal 1'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Large language models (LLMs) have demonstrated impressive capabilities in various natural language processing tasks. Despite this, their application to information retrieval (IR) tasks is still challenging due to the infrequent occurrence of many IR-specific concepts in natural language. While prompt-based methods can provide task descriptions to LLMs, they often fall short in facilitating comprehensive understanding and execution of IR tasks, thereby limiting LLMs' applicability. To address this gap, in this work, we explore the potential of instruction tuning to enhance LLMs' proficiency in IR tasks. We introduce a novel instruction tuning dataset, INTERS, encompassing 21 tasks across three fundamental IR categories: query understanding, document understanding, and query-document relationship understanding. The data are derived from 43 distinct datasets with manually written templates. Our empirical results reveal that INTERS significantly boosts the performance of various publicly available LLMs, such as LLaMA, Mistral, and Phi, in search-related tasks. Furthermore, we conduct a comprehensive analysis to ascertain the effects of base model selection, instruction design, volume of instructions, and task variety on performance. We make our dataset and the models fine-tuned on it publicly accessible at [this https URL](https://github.com/DaoD/INTERS).

[arxiv](https://arxiv.org/abs/2401.06532)

Recommended citation:
```BibTex
@article{Inters,
    author={Yutao Zhu and
            Peitian Zhang and
            Chenghao Zhang and
            Yifei Chen and
            Binyu Xie and
            Zhicheng Dou and
            Zheng Liu and
            Ji-Rong Wen},
    title={INTERS: Unlocking the Power of Large Language Models in Search with Instruction Tuning},
    journal={CoRR},
    volume={abs/2401.06532},
    year={2024},
    url={https://arxiv.org/abs/2401.06532},
    eprinttype={arXiv},
    eprint={}
}
```
