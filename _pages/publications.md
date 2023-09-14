---
layout: archive
title: "Ongoing Papers: "
permalink: /publications/
author_profile: true
---

[diffIRM: A Diffusion-Augmented Invariant Risk Minimization Framework for Spatiotemporal Prediction over Graphs](https://haotianxiangsti.github.io/haotianxiang.github.io/files/TSAS2023.pdf)
===
<img src="https://haotianxiangsti.github.io/haotianxiang.github.io/images/flowchart_1.jpg">

**Haotian Xiang**, Zhaobin Mo, Lindong Liu, Sharon Di*



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
