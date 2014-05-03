---
layout: default
title: Projects
---

*This page lists my current projects - for more information please visit their dedicated websites.*

<p>&nbsp;</p>
{% for project in site.projects %}
<div class="row">
  <div class="col-md-12">
    <img src="images/{{ project.image }}" class="icon">
    <h3>{{ project.name }}</h3>
    {{ project.content | markdownify }}
    <p>&nbsp;</p>
  </div>
</div>
{% endfor %}
