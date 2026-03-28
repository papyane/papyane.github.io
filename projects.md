---
layout: default
title: Projects
permalink: /projects/
---

<div class="projects-container">
  <h1 class="page-title">Projects</h1>

  <div class="project-list">
    {% for project in site.data.projects %}
      <div class="project-row">
        
        <div class="project-image">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}">
        </div>
        
        <div class="project-details">
          <h2>{{ project.title }}</h2>
          <p class="project-date">{{ project.date }}</p>
          <p class="project-desc">{{ project.description }}</p>
        </div>

      </div>
    {% endfor %}
  </div>
</div>
