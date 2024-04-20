---
title: "Improving search with supervised learning in trick-based card games"
collection: publications
permalink: /publication/2019-07-17-trick-taking
excerpt: 'This paper uses deep learning to approximate factored belief distributions for search in a trick-taking card game called Skat.'
date: 2019-07-17
venue: 'AAAI'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/3909/3787'
---

In trick-taking card games, a two-step process of state sampling and evaluation is widely used to approximate move values. While the evaluation component is vital, the accuracy of move value estimates is also fundamentally linked to how well the sampling distribution corresponds to the true distribution. Despite this, recent work in trick-taking card game AI has mainly focused on improving evaluation algorithms with limited work on improving sampling. In this paper, we focus on the effect of sampling on the strength of a player and propose a novel method of sampling more realistic states given move history. In particular, we use predictions about the locations of individual cards made by a deep neural network—trained on data from human gameplay—to sample likely worlds for evaluation. This technique, used in conjunction with Perfect Information Monte Carlo (PIMC) search, provides a substantial increase in cardplay strength in the popular trick-taking card game Skat.
