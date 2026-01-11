---
layout: page
title: Mes Projets
permalink: /projects/
---

Voici les projets techniques que j'ai réalisés :

<ul>
  {% for project in site.projects %}
    <li>
      <h3>
        <a href="{{ project.url | relative_url }}">{{ project.title }}</a>
      </h3>
      <p>{{ project.description }}</p>
    </li>
  {% endfor %}
</ul>