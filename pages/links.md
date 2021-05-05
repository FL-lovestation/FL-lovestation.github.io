---
layout: page
title: Links
menu: 链接
permalink: /links/
---

> 恋爱日常

<ul>
{% for link in site.data.links %}
  {% if link.src == 'love' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>

> 学习、工作和生活

<ul>
{% for link in site.data.links %}
  {% if link.src == 'life' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>
