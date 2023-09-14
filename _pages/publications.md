---
layout: archive
title: "Ongoing Papers"
permalink: /publications/
author_profile: true
---
<img src="https://haotianxiangsti.github.io/haotianxiang.github.io/images/flowchart_1.jpg" alt="图片描述">
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
