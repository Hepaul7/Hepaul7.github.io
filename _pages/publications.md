---
layout: page
permalink: /research/
title: research
description: Some research projects I've been doing
nav: false
nav_order: 2
---

[//]: # (<!-- _pages/publications.md -->)

[//]: # (<div class="publications">)

[//]: # ()
[//]: # ({% bibliography %})

[//]: # ()
[//]: # (</div>)

### Current Research Projects
1. Large Language Models, Attention, Information Theory

### Speeding up Earley's Algorithm with A* Search
Earley's algorithm can parse unrestricted context-free grammar in $\mathcal{O}(N^3|\mathcal{G}||\mathcal{P}|)$ runtime. In this paper, we reformulate Earley's algorithm as a search problem and introduce the application of A* heuristics to enhance the efficiency of the parser. Our approach leverages the strength of A* search to prune the search space effectively, thus accelerating the parsing procedure while still being complete and finite. We provide a detailed description of our formulation, discuss the impact of different heuristics on the algorithm's performance, and present empirical results to demonstrate the improvements achieved.
(Author ordering is random).
[Download PDF (Paper)](/assets/pdf/A_star_Earley.pdf)

[//]: # (### Improving the Expected Runtime of Earley's Algorithm with A* Search)

[//]: # (_NLP, Parsing, Algorithms_)

[//]: # ()
[//]: # (This is my current research project.)

[//]: # ()
[//]: # (Consider the objective of the Earley’s algorithm as a search problem, where we want one possible parse of the input string, or declare that it is not recognized.)

[//]: # (In Earley’s algorithm, an item represents a partially completed parse tree. We start the search from a start item, and explore new items iteratively until the goal item is found. As soon as we have found the goal item, we can immediately produce one possible parse tree. Unless we need other parse trees as well, we do not need to explore further.)

[//]: # (For a WCFG, where our search problem still remains the same, we ask the following questions:)

[//]: # (- Can we find a path from a start item to a goal item quickly?)

[//]: # (- Can we find an optimal path from a start item to a goal item quickly?)

### Joint Chinese Word Segmentation and Parts of Speech Tagging with the Transformer

[//]: # (_NLP, Transformers_)

Chinese text analysis presents unique challenges, as words in Chinese sentences are not demarcated, making tasks like part-of-speech (POS) tagging and Chinese word segmentation (CWS) essential preliminary steps. This paper explores the effectiveness using the Transformer architecture to perform joint CWS and POS tagging, where BERT embedding are used to encode contextual information. We were able to achieve strong performances with significantly fewer training resources.

[//]: # ([Download PDF &#40;Paper&#41;]&#40;/assets/pdf/CWSPOS.pdf&#41;)

[View code on GitHub](https://github.com/Hepaul7/SegPosCN)

