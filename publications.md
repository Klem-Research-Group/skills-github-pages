---
layout: default
title: Publications
---
<h1>Our Publications</h1>
<ul>
{% for pub in site.publications %}
  <li><a href="{{ pub.url }}">{{ pub.title }}</a> by {{ pub.authors }}</li>
{% endfor %}
</ul>
