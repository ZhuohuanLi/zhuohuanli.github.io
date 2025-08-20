---
layout: home
title: About Me
---

I am a fourth-year PhD student at Rutgers University. I'm fortunate to be advised by [Prof. Karl Stratos](http://karlstratos.com/). I received M.S. in CS from Rutgers in Spring 2021. Prior to RU, I graduated from University of Science and Technology of China with a B.S. in Applied Physics.  My research focuses on two closely connected areas in natural language processing: **Information Retrieval and Retrieval-Augmented Generation** and **Entity-Centric Language Understanding**. I remain open to exploring other exciting and impactful research directions. 

## Information Retrieval and Retrieval-Augmented Generation
I conduct extensive research on improving **information retrieval (IR)** and **retrieval-augmented generation (RAG)** for knowledge-intensive tasks. My key contributions include:

- **Theoretical Analysis of Hard Negatives in NCE**: Provided a theoretical understanding of the role of hard negatives in the Noise Contrastive Estimation (NCE) training objective for retrievers by showing that using hard negatives reduces the bias between the NCE approximation and the ideal cross-entropy loss computed over all candidates in the knowledge base (**Hard-NCE**).
- **Multi-Label NCE for Multi-Target Retrieval**: Extended the standard NCE objective to a Multi-Label NCE formulation, enabling support for retrieval scenarios with multiple valid target candidates—such as entity-rich or multi-answer tasks—beyond traditional single-label setups.
- **Multi-Task Retriever Training**: Developed multi-task training strategies to train a single retriever that performs well across diverse knowledge-intensive tasks by encouraging task specialization within the model.
- **Unifying Retriever and Generator for RAG**: Unified retriever and generator by dividing decoder layers into specialized groups for joint optimization, enabling implicit query formulation and improving alignment between retrieval and generation (**ImpRAG**).


## Entity-Centric Language Understanding
I explore how language models can better understand and resolve references to entities, both within text (**coreference resolution**) and against external knowledge bases (**entity linking**). My key contributions include:

- **Entity Linking**: Reformulated entity linking as inverse open-domain QA—first retrieving candidate entities, then detecting mentions conditioned on each entity. This avoids the ill-defined nature of detecting mentions without entity context and offers a new paradigm for entity linking (**EntQA**).
- **Coreference Resolution**: Proposed a simple and elegant sequence-to-sequence model that generates coreference information in the target sequence directly, avoiding span enumeration, pruning strategies, or complex model design, while achieving state-of-the-art performance (**Seq2Seq-Coref**).



## Papers
#### [ImpRAG: Retrieval-Augmented Generation with Implicit Queries](https://arxiv.org/pdf/2506.02279)

**Wenzheng Zhang**, Xi Victoria Lin, Karl Stratos, Wen-tau Yih, Mingda Chen. Findings of EMNLP 2025.

#### [Seq2seq is All You Need for Coreference Resolution](https://arxiv.org/pdf/2310.13774.pdf)

**Wenzheng Zhang**, Sam Wiseman, Karl Stratos. EMNLP 2023. [[code](https://github.com/WenzhengZhang/Seq2seqCoref)]

#### [Improving Multitask Retrieval by Promoting Task Specialization](https://arxiv.org/pdf/2307.00342.pdf)

**Wenzheng Zhang**, Chenyan Xiong, Karl Stratos, Arnold Overwijk. TACL 2023. [[code](https://github.com/WenzhengZhang/TACO)]

#### [EntQA: Entity Linking as Question Answering](https://arxiv.org/pdf/2110.02369.pdf)

**Wenzheng Zhang**, Wenyue Hua, Karl Stratos. ICLR 2022 <span style="color:olivegreen">*Spotlight* </span>. [[code](https://github.com/WenzhengZhang/EntQA)]

#### [Understanding Hard Negatives in Noise Contrastive Estimation](https://aclanthology.org/2021.naacl-main.86.pdf)

**Wenzheng Zhang**, Karl Stratos. NAACL 2021. [[code](https://github.com/WenzhengZhang/hard-nce-el)]

## Academic Internships
#### **Microsoft**

worked with [Prof. Chenyan Xiong](https://scholar.google.com/citations?user=E9BaEBYAAAAJ&hl=en) and [Arnold Overwijk](https://scholar.google.com/citations?user=zKiMGDgAAAAJ&hl=en), Jun 2022 -- Sep 2022



#### **Meta FAIR**

worked with [Dr. Mingda Chen](https://mingdachen.github.io/), [Dr. Scott Yih](https://scottyih.org/) and [Dr. Victoria Lin](https://victorialin.net/), May 2024 -- Dec 2024





