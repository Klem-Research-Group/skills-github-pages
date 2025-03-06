---
layout: default
title: People
---
<h1>Meet Our Team</h1>
<ul>
{% for person in site.people %}
  <li><a href="{{ person.url }}">{{ person.name }}</a> - {{ person.role }}</li>
{% endfor %}
</ul>
