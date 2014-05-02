---
layout: default
title: Projects
---

*This page lists my current projects - for more information please visit their dedicated websites.*

{% for project in site.projects %}
  <h1>{{ project.name }}</h1>
  <p>{{ project.content | markdownify }}</p>
  <img src="images/{{ project.image }}">
{% endfor %}
