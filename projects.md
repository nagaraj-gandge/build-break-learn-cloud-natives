---
layout: page
title: Projects
permalink: /projects/
---

Browse all project entries:

<ul>
{% for project in site.projects %}
  <li>
    <a href="{{ project.url | relative_url }}">{{ project.title }}</a>
    {% if project.description %} - {{ project.description }}{% endif %}
  </li>
{% endfor %}
</ul>
