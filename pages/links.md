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

> 学习与工作

<ul>
{% for link in site.data.links %}
  {% if link.src == 'study_work' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>

> 好吃的

<ul>
{% for link in site.data.links %}
  {% if link.src == 'food' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>

> 好玩的

<ul>
{% for link in site.data.links %}
  {% if link.src == 'play' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>
