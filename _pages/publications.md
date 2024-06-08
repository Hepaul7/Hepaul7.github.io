---
layout: page
permalink: /research/
title: research
description: Some research projects I've been doing
nav: true
nav_order: 2
---

[//]: # (<!-- _pages/publications.md -->)

[//]: # (<div class="publications">)

[//]: # ()
[//]: # ({% bibliography %})

[//]: # ()
[//]: # (</div>)

### Current Research
I have two ongoing research projects and papers roughly on the topics of
1. Earley's Algorithm, Parsing, Runtime
2. Large Language Models, Attention, Information Theory

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
_NLP, Transformers_

Chinese text analysis presents unique challenges, as words in Chinese sentences are not demarcated, making tasks like part-of-speech (POS) tagging and Chinese word segmentation (CWS) essential preliminary steps. This paper explores the effectiveness using the Transformer architecture to perform joint CWS and POS tagging, where BERT embedding are used to encode contextual information. We were able to achieve strong performances with significantly fewer training resources.

[Download PDF (Paper)](/assets/pdf/CWSPOS.pdf)

[View code on GitHub](https://github.com/Hepaul7/SegPosCN)

