---
layout: default
title: News
---
<h1>Latest News</h1>
<ul>
{% for item in site.news %}
  <li><a href="{{ item.url }}">{{ item.title }}</a> - {{ item.date }}</li>
{% endfor %}
</ul>
