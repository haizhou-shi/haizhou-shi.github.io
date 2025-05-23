---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my personal website! I'm Haizhou Shi (史海舟), a third-year Ph.D. student in the [CS Department at Rutgers University](https://www.cs.rutgers.edu), advised by Prof. [Hao Wang](http://wanghao.in). My research focuses on developing reliable and efficient methods for adapting machine learning models. I'm currently exploring two main areas: **continual training of Large Language Models (LLMs)** - including continued pre-training, post-training, and alignment - and **uncertainty estimation in LLMs** through Bayesian Deep Learning approaches. 

Prior to Rutgers, I received my M.S. and B.S. degrees from the CS Department at Zhejiang University in 2022 and 2019, where I worked with Prof. [Siliang Tang](https://scholar.google.com/citations?user=8e7H3PcAAAAJ&hl=en) and [Yueting Zhuang](https://scholar.google.com/citations?user=1RD7UJAAAAAJ&hl=en). My research there focused on developing generalizable representations across various learning paradigms, including unsupervised, weakly-supervised, federated, and continual learning.

<!-- ----
**Job Hunting**: I am now actively looking for the internship opportunity in Summer 2024! *I am interested in working on the topics of (but not limited to) continual pre-training/adaptation for LLMs/large generative models.*
Please contact me if you are interested (and happen to have an opening in your team 🥹)! -->

----
# News
- [05/2025] *Our [survey](https://arxiv.org/abs/2404.16789) on <u>Continual Learning of LLMs</u> got accepted at **CSUR**!*
- [05/2025] *Our [paper](https://arxiv.org/abs/2502.03628) on <u>Dehalluciation of LVLMs</u> got accepted at **ICML 2025**!*
- [02/2025] *Our [paper](https://arxiv.org/abs/2412.05723) on <u>Training-Free Bayesianization for LLMs</u> got accepted at [ICLR 2025 "QUESTION" Workshop](https://uncertainty-foundation-models.github.io)!*
- [01/2025] *I will join [Salesforce AI Reseach](https://www.salesforceairesearch.com) as a research intern in summer 2025!*
- [01/2025] *Our [paper](https://arxiv.org/abs/2406.11230) on <u>Benchmarking Multimodal LLMs</u> got accepted at **NAACL 2025**!*
- [01/2025] *I gave a [talk](https://drive.google.com/file/d/1a5byNlTK30RFnBnqPEyypOt3Eovs54qT/view?usp=share_link) on <u>Bayesian Uncertainty Estimation for LLMs</u> at [Red Hat](https://www.redhat.com/en).*
- [09/2024] *Our [paper](https://arxiv.org/abs/2406.11675) on <u>Bayesian Low-Rank Adaptation for LLMs</u> got accepted at **NeurIPS 2024**!* 
- [01/2024] *I will join [Morgan Stanley ML Research](https://www.morganstanley.com/about-us/technology/machine-learning-research-team) as a research intern in summer 2024!*
- [09/2023] *Our [paper](https://arxiv.org/abs/2310.12244) on <u>Domain Incremental Learning</u> got accepted at **NeurIPS 2023**!*
- [09/2022] *I was fortunate to join Rutgers as a Ph.D. student, to work with Prof. [Hao Wang](http://wanghao.in)!*
- [02/2022] *Our [paper](https://arxiv.org/abs/2109.14611) on <u>Federated Representation Learning</u> got accepted at **AAAI-FL-2022** workshop as oral presentation!*
- [12/2021] *Our [paper](https://arxiv.org/abs/2107.14762) on <u>Lightweight Representation Learning</u> got accepted at **AAAI 2022** as **oral presentation (top \~1.6%)**!*


----
# Selected Publications 

(where selection is completely based on my own bias, and "*" denotes equal contribution)

{% for post in site.publications reversed %}
  {% if post.selected %}
  {% include archive-pub-short.html %}
  {% endif %}
{% endfor %}