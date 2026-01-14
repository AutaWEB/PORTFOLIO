---
layout: default
title: Mes Projets
permalink: /projects.html
---

<h1>Mes Projets Epitech</h1>

<div class="projects-container">
  {% for project in site.projects %}
    <div class="project-card">
      <h2><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h2>
      <p>{{ project.description }}</p>
    </div>
  {% endfor %}
</div>