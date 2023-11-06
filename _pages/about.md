---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my personal website! I'm Haizhou Shi (史海舟), a second-year Ph.D. student in the [CS Department at Rutgers University](https://www.cs.rutgers.edu), working under the guidance of Prof. [Hao Wang](http://wanghao.in). *My research centers on enhancing machine learning models' generalization abilities, enabling them to adapt quickly to evolving learning tasks and data distributions.*

Previous to that, I earned my M.S. and B.S. degrees from the [CS Department at Zhejiang University](http://www.en.cs.zju.edu.cn) in 2022 and 2019, under the supervision of Prof. [Siliang Tang](https://person.zju.edu.cn/en/siliang) and [Yueting Zhuang](https://person.zju.edu.cn/en/yzhuang). During that time, my focus was on developing generalizable representations in various scenarios, including unsupervised, weakly-supervised, federated, and continual learning.

----
**Job Hunting**: I am now actively looking for the internship opportunity in Summer 2024! *I am interested in working on the topics of (but not limited to) continual pre-training/adaptation for LLMs/large generative models.*
Please contact me if you are interested (and happen to have an opening in your team 🥹)!

----
# News
- 09/2023: *one paper got accepted at NeurIPS 2023! See you in New Orleans!*
- 07/2023: *one paper got accepted at ECAI 2023!*
- 09/2022: *I was fortunate to join Rutgers as a Ph.D. student, to work with Prof. [Hao Wang](http://wanghao.in)!*
- 06/2022: *I earned my M.S. from the CS Department at Zhejiang University. Many thanks to my advisor Prof. [Siliang Tang](https://person.zju.edu.cn/en/siliang) and [Yueting Zhuang](https://person.zju.edu.cn/en/yzhuang)!*
- 02/2022: *one paper got accepted at AAAI-FL-2022 workshop as oral presentation!*
- 12/2021: *one paper got accepted at AAAI 2022 as oral presentation!*


----
# Selected Publications 

(where selection is completely based on my own bias, and "*" denotes equal contribution)

{% for post in site.publications reversed %}
  {% if post.selected %}
  {% include archive-pub-short.html %}
  {% endif %}
{% endfor %}