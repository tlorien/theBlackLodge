---
layout: index
title: "Projects"
permalink: /projects/
---

# My GitHub Projects

<p>My GitHub repositories:</p>

<ul>
  {% for project in site.data.projects %}
    <li>
      <a href="{{ project.url }}" target="_blank">{{ project.name }}</a>: {{ project.description }}
    </li>
  {% endfor %}
</ul>
