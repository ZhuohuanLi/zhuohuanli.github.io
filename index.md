---
layout: home
title: About Me
---

I am a fourth-year PhD student at Rutgers University. I'm fortunate to be advised by [Prof. Karl Stratos](http://karlstratos.com/). I received M.S. in CS from Rutgers in Spring 2021. Prior to RU, I graduated from University of Science and Technology of China with a B.S. in Applied Physics.  My research focuses on two closely connected areas in natural language processing: **Entity-Centric Language Understanding** and **Improving Information Retrieval and Retrieval-Augmented Generation**. I remain open to exploring other exciting and impactful research directions. 

## Entity Centric Language Understanding
I explore how language models can better understand and resolve references to entities, both within text (coreference resolution) and against external knowledge bases (entity linking). My key contributions include:

- Entity Linking: Traditional approaches follow a two-stage pipeline of mention detection (MD) followed by entity retrieval (ER). In contrast, we propose a novel formulation that treats entity linking as an inverse open-domain question answering task (EntQA). Our method first retrieves potentially mentioned entities based on semantic similarity to the input text, and then performs conditional mention detection to identify the spans referring to each retrieved entity. This flip the order of the standard MD→ER pipeline and addresses a fundamental weakness in prior work: since a mention is defined only in relation to a specific entity, detecting mentions without entity context is inherently ill-defined, while retrieving entities without knowing exact mentions is much easier. I believe this represents a paradigm shift in how the entity linking task can be approached.

- Coreference Resolution: Prior methods largely rely on span-based models that match mention pairs through embedding similarity, requiring complex architectures and extensive hyperparameter tuning to manage the combinatorial search space. We instead propose a simple and elegant solution: framing coreference resolution as a sequence-to-sequence task. Our model (Seq2Seq-Coref) directly generates coreference information in the target sequence, removing the need for span enumeration, pruning strategies, or intricate model design. This approach achieves state-of-the-art performance with a significantly simpler and more natural framework—representing, in my view, a fundamental shift in how coreference resolution can be modeled.

## Improving Information Retrieval and Retrieval-Augmented Generation
I conduct extensive research on improving information retrieval (IR) and retrieval-augmented generation (RAG) for knowledge-intensive tasks. My key contributions include:

- Theoretical Analysis of Hard Negatives in NCE: I provide a theoretical understanding of the role of hard negatives in the Noise Contrastive Estimation (NCE) training objective for retrievers. Specifically, I show that using hard negatives (Hard-NCE) reduces the bias between the NCE approximation and the ideal cross-entropy loss computed over all candidates in the knowledge base.

- Multi-Label NCE for Multi-Target Retrieval: I extend the standard NCE objective to a Multi-Label NCE formulation, enabling support for retrieval scenarios with multiple valid target candidates—such as entity-rich or multi-answer tasks—beyond traditional single-label setups.

- Multi-Task Retriever Training: I develop multi-task training strategies to train a single retriever that generalizes across diverse knowledge-intensive tasks. This is achieved by encouraging task specialization within the model, improving both task-specific performance and generalization.

- Unifying Retriever and Generator (ImpRAG): I propose ImpRAG, a retrieval-augmented generation model that integrates retriever and generator into a single unified architecture. By dividing decoder layers into specialized groups and optimizing jointly for retrieval and generation, ImpRAG eliminates the need for explicit, task-specific query templates. This reduces misalignment between retrieval and generation while enabling the model to implicitly express its information needs.






**I am actively seeking research scientist or engineer roles. Please feel free to reach out if you'd like to discuss opportunities.**

## Papers
#### [ImpRAG: Retrieval-Augmented Generation with Implicit Queries](https://arxiv.org/pdf/2506.02279)

**Wenzheng Zhang**, Xi Victoria Lin, Karl Stratos, Wen-tau Yih, Mingda Chen. In Submission.

#### [Seq2seq is All You Need for Coreference Resolution](https://arxiv.org/pdf/2310.13774.pdf)

**Wenzheng Zhang**, Sam Wiseman, Karl Stratos. EMNLP 2023. [[code](https://github.com/WenzhengZhang/Seq2seqCoref)]

#### [Improving Multitask Retrieval by Promoting Task Specialization](https://arxiv.org/pdf/2307.00342.pdf)

**Wenzheng Zhang**, Chenyan Xiong, Karl Stratos, Arnold Overwijk. TACL 2023. [[code](https://github.com/WenzhengZhang/TACO)]

#### [EntQA: Entity Linking as Question Answering](https://arxiv.org/pdf/2110.02369.pdf)

**Wenzheng Zhang**, Wenyue Hua, Karl Stratos. ICLR 2022 <span style="color:olivegreen">*Spotlight* </span>. [[code](https://github.com/WenzhengZhang/EntQA)]

#### [Understanding Hard Negatives in Noise Contrastive Estimation](https://aclanthology.org/2021.naacl-main.86.pdf)

**Wenzheng Zhang**, Karl Stratos. NAACL 2021. [[code](https://github.com/WenzhengZhang/hard-nce-el)]

## Academic Internships
#### **Microsoft Research**

worked with [Prof. Chenyan Xiong](https://scholar.google.com/citations?user=E9BaEBYAAAAJ&hl=en) and [Arnold Overwijk](https://scholar.google.com/citations?user=zKiMGDgAAAAJ&hl=en), Jun 2022 -- Sep 2022



#### **Meta FAIR**

worked with [Dr. Mingda Chen](https://mingdachen.github.io/), [Dr. Scott Yih](https://scottyih.org/) and [Dr. Victoria Lin](https://victorialin.net/), May 2024 -- Dec 2024





