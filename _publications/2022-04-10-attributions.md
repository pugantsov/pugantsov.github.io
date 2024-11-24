---
title: "Identifying Suitable Tasks for Inductive Transfer Through the Analysis of Feature Attributions"
collection: publications
category: conferences
permalink: /publication/2022-04-10-attributions
excerpt: 'Transfer learning often improves downstream task performance, but finding effective task pairings is computationally expensive due to trial-and-error. This paper predicts transferability between tasks using explainability techniques, comparing neural network activations of single-task models. Our approach reduces training time by up to 83.5% with minimal impact on performance.'
date: 2022-04-10
venue: 'European Conference on Information Retrieval'
paperurl: 'https://arxiv.org/abs/2202.01096'
citation: 'Pugantsov, A., & McCreadie, R. (2022). Identifying Suitable Tasks for Inductive Transfer Through the Analysis of Feature Attributions. In <i>European Conference on Information Retrieval</i> (pp. 137-143).'
---

Transfer learning approaches have shown to significantly improve performance on downstream tasks. However, it is common for prior works to only report where transfer learning was beneficial, ignoring the significant trial-and-error required to find effective settings for transfer. Indeed, not all task combinations lead to performance benefits, and brute-force searching rapidly becomes computationally infeasible. Hence the question arises, can we predict whether transfer between two tasks will be beneficial without actually performing the experiment? In this paper, we leverage explainability techniques to effectively predict whether task pairs will be complementary, through comparison of neural network activation between single-task models. In this way, we can avoid grid-searches over all task and hyperparameter combinations, dramatically reducing the time needed to find effective task pairs. Our results show that, through this approach, it is possible to reduce training time by up to 83.5% at a cost of only 0.034 reduction in positive-class F1 on the TREC-IS 2020-A dataset.
