---
title: "Understand What LLM Needs: Dual Preference Alignment for Retrieval-Augmented Generation"
collection: publications
permalink: /publication/dpa
excerpt: 'DPA-RAG is a universal framework for aligning diverse preference knowledge within RAG systems, consisting of three main components: Preference Knowledge Construction, Reranker-LLM Alignment and LLM Self-Alignment.'
date: 2024-07-18
venue: 'arXiv'
paperurl: 'http://snownation101.github.io/files/DPA.pdf'
citation: 'Yutao Zhu, Peitian Zhang, Chenghao Zhang, Yifei Chen, Binyu Xie, Zhicheng Dou, Zheng Liu, Ji-Rong Wen: INTERS: Unlocking the Power of Large Language Models in Search with Instruction Tuning. CoRR abs/2401.06532 (2024)'
---

Retrieval-augmented generation (RAG) has demonstrated effectiveness in mitigating the hallucination problem of large language models (LLMs). However, the difficulty of aligning the retriever with the diverse LLMs' knowledge preferences inevitably poses an inevitable challenge in developing a reliable RAG system. To address this issue, we propose DPA-RAG, a universal framework designed to align diverse knowledge preferences within RAG systems. Specifically, we initially introduce a preference knowledge construction pipline and incorporate five novel query augmentation strategies to alleviate preference data scarcity. Based on preference data, DPA-RAG accomplishes both external and internal preference alignment: (1) It jointly integrate pair-wise, point-wise, and contrastive preference alignment abilities into the reranker, achieving external preference alignment among RAG components. (2) It further introduces a pre-aligned stage before vanilla Supervised Fine-tuning (SFT), enabling LLMs to implicitly capture knowledge aligned with their reasoning preferences, achieving LLMs' internal alignment. Experimental results across four knowledge-intensive QA datasets demonstrate that DPA-RAG outperforms all baselines and seamlessly integrates both black-box and open-sourced LLM readers. Further qualitative analysis and discussions also provide empirical guidance for achieving reliable RAG systems. Our code is publicly available at [THIS URL](https://github.com/dongguanting/DPA-RAG).
