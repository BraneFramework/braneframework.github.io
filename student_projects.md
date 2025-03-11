---
layout: page
title: Student projects
permalink: /student_projects/
---
{% for project in site.student_projects %}
  <h2>
    <a href="{{ project.url }}">
      {{ project.name }} - {{ project.size }}
    </a>
  </h2>
  <p>{{ project.content | markdownify }}</p>
{% endfor %}

