---
layout: page
title: Topics
permalink: /topics/
---

Browse my notes and write-ups by topic:

<ul>
{% for item in site.data.sections %}
  <li><a href="{{ '/' | append: item.path | relative_url }}">{{ item.title }}</a></li>
{% endfor %}
</ul>
