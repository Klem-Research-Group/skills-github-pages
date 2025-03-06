---
layout: default
title: Research
---
<h1>Our Research</h1>
<p>Our group focuses on the following areas of research:</p>
<ul>
{% for item in site.research %}
  <li><a href="{{ item.url }}">{{ item.title }}</a>: {{ item.description }}</li>
{% endfor %}
</ul>
