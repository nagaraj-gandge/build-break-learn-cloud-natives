---
layout: home
title: Welcome
---

## Hi, I'm a Developer
Welcome to my portfolio. Below are some of my highlighted projects.

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url | relative_url }}) -€” {{ project.description }}
{% endfor %}

