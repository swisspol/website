---
layout: default
title: Open Source
---

*This page contains the source code of some of my current and past projects. This source code is available for free and "as-is", with no warranty of any kind.*

{% for project in site.open_source %}
  <h1>{{ project.name }}</h1>
  <p>{{ project.content | markdownify }}</p>
  <img src="images/{{ project.image }}">
{% endfor %}
