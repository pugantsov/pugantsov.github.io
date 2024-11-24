---
title: "Divergence-Based Domain Transferability for Zero-Shot Classification"
collection: publications
category: conferences
permalink: /publication/2023-09-23-divergence
excerpt: 'Fine-tuning on intermediate tasks can enhance pretrained language models, but identifying related tasks is challenging and resource-intensive. This paper uses statistical measures of domain divergence to predict which task pairs are likely to yield performance benefits. Our method reduces the number of task combinations to test, cutting runtime by up to 40% while maintaining effectiveness.'
date: 2023-09-23
venue: 'European Chapter of the Association for Computational Linguistics'
paperurl: 'https://aclanthology.org/2023.findings-eacl.122.pdf'
citation: 'Pugantsov, A., & McCreadie, R. (2023). Divergence-Based Domain Transferability for Zero-Shot Classification. In <i>Findings of the Association for Computational Linguistics: EACL 2023</i> (pp. 1649-1654).'
---

Transferring learned patterns from pretrained neural language models has been shown to significantly improve effectiveness across a variety of language-based tasks, meanwhile further tuning on intermediate tasks has been demonstrated to provide additional performance benefits, provided the intermediate task is sufficiently related to the target task. However, how to identify related tasks is an open problem, and brute-force searching effective task combinations is prohibitively expensive. Hence, the question arises, are we able to improve the effectiveness and efficiency of tasks with no training examples through selective fine-tuning? In this paper, we explore statistical measures that approximate the divergence between domain representations as a means to estimate whether tuning using one task pair will exhibit performance benefits over tuning another. This estimation can then be used to reduce the number of task pairs that need to be tested by eliminating pairs that are unlikely to provide benefits. Through experimentation over 58 tasks and over 6,600 task pair combinations, we demonstrate that statistical measures can distinguish effective task pairs, and the resulting estimates can reduce end-to-end runtime by up to 40%.

[Paper](https://aclanthology.org/2023.findings-eacl.122/)
