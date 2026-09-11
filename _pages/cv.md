---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **Ph.D. in Computer Science** (2024–Present), Hong Kong University of Science and Technology
  * HKUST NLP Group
  * Supervisor: Professor Junxian He
* **B.Eng.** (2020–2024), Shanghai Jiao Tong University
  * Recipient of the Zhiyuan Honor Scholarship

## Work Experience

* **Research Intern**, MINIMAX (February 2025 – Present)
* **Research Intern**, Tencent WXG (June 2024 – September 2024)
  * Supervisor: Zifei Shan
* **Research Intern**, Shanghai AI Lab (June 2023 – December 2023)
  * Supervisor: Professor Yu Cheng

## Skills

* **Programming:** Python, PyTorch, Linux
* **Languages:** English, Mandarin Chinese
* **NLP & Machine Learning:** Large Language Models, Reinforcement Learning, Vision-Language Models, Chain-of-Thought Reasoning, Truthfulness and Interpretability
* **Tools:** LaTeX, Git, Docker

## Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>