---
layout: default
title: Homepage
---

# Welcome to AlwaysFree

## Categories

<ul>
{% for category in site.categories %}
  <li><a href="/categories/{{ category[0] | replace: " ", "-" }}/">{{ category[0] }}</a></li>
{% endfor %}
</ul>
