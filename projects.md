---
layout: default
title: Projects
permalink: /projects/
---

# Projects

Stuff?

<div class="project-list">
  {% for project in site.data.projects %}
    <div class="project-item">
      <h3><a href="{{ project.link }}">{{ project.title }}</a></h3>
      <p>{{ project.description }}</p>
    </div>
  {% endfor %}
</div>