---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**Du Chen**, Yuming Deng, Guangrui Ma, Hao Ge, Yunwei Qi, Ying Rong, Xun
Zhang, and Huan Zheng*.
[Inventory Based Recommendation Algorithms](https://raw.githubusercontent.com/chendu2017/selected_works/master/Inventory%20Based%20Recommendation%20Algorithms.pdf),
accepted at *2020 IEEE International Conference on Big Data*,
forthcoming.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
