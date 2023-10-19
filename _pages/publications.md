---
layout: archive
title: "Ongoing Papers: "
permalink: /publications/
author_profile: true
---

[diffIRM: A Diffusion-Augmented Invariant Risk Minimization Framework for Spatiotemporal Prediction over Graphs](https://haotianxiangsti.github.io/haotianxiang.github.io/files/Haotian_Xiang_Abstract_AISTATS_24.pdf)
===
<img src="https://haotianxiangsti.github.io/haotianxiang.github.io/images/flowchart (1).jpg">

**Haotian Xiang**^, Zhaobin Mo^, Lindong Liu^, Sharon Di*

The Draft Paper is completed and it is aiming for [AIStat 2024](http://aistats.org/aistats2024/)

[Cross- and Context-Aware Attention Based Spatial-Temporal Graph Convolutional Networks for Human Mobility Prediction](https://haotianxiangsti.github.io/haotianxiang.github.io/files/TSAS2023.pdf)
===
<img src="https://haotianxiangsti.github.io/haotianxiang.github.io/images/architecture.png">

Zhaobin Mo, **Haotian Xiang**, Eric Chang, Sharon Di*

The paper is submitted to [ACM Transactions on Spatial Algorithms and Systems](https://dl.acm.org/journal/tsas) workshops 2023

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

^ Equal Contribution, * Corresponding Author