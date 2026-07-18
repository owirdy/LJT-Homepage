---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About Me

I am a first-year Ph.D. candidate in Computer Science at the **Hong Kong University of Science and Technology (HKUST)**, working with [Professor Junxian He](https://jxhe.github.io/) in the **HKUST NLP Group**. I graduated with a B.Eng. from **Shanghai Jiao Tong University (SJTU)** in June 2024, where I was also advised by Professor Junxian He.

My research focuses on **Natural Language Processing** and **Machine Learning**, with specific interests in:

- **LLM Reasoning and Reinforcement Learning**
- **Hallucination in Vision-Language Models (VLMs)**
- **LLM Truthfulness and Interpretability**

I have been a Research Intern at **MINIMAX** (Feb 2025 -- Present), **Tencent WXG** (Jun 2024 -- Sep 2024, advised by Zifei Shan), and **Shanghai AI Lab** (Jun 2023 -- Dec 2023, advised by Prof. Yu Cheng).

I received the **Zhiyuan Honor Scholarship** at Shanghai Jiao Tong University.

## Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
