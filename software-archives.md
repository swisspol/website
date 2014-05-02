---
layout: default
title: Software Archives
---

*This page lists most software I have developed as an independent in the past, but which are not distributed anymore (freeware, shareware or commercial licenses). For software developed while working at companies, see the full list on the right side.*

{% for project in site.software_archives %}
  <h1>{{ project.name }} ({{ project.release }})</h1>
  <p>{{ project.content | markdownify }}</p>
  <img src="images/{{ project.image }}">
{% endfor %}
