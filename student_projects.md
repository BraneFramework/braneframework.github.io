---
layout: page
title: Student projects
permalink: /student_projects/
---

Most of the time there are some student projects available for students of the University of Amsterdam and Vrij Universeiteit. These projects are for the courses:

 - Web services and cloud based systems (UvA: 5284WSCB6Y).
 - Research Project Computer Science (VU: XM_0129) 6 EC
 - Large Research Project Computer Science (VU: XM_0130) 12 EC
 - Literature study (VU: XM_0131)

<hr>

{% for project in site.student_projects %}
  <h2>
    <a href="{{ project.url }}">
      {{ project.name }} - {{ project.size }}
    </a>
  </h2>
  <p>{{ project.content | markdownify }}</p>
{% endfor %}

