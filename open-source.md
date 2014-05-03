---
layout: default
title: Open Source
---

*This page contains the source code of some of my current and past projects. This source code is available for free and "as-is", with no warranty of any kind.*

<p>&nbsp;</p>
{% for project in site.open_source %}
<div class="row">
  <div class="col-md-12">
    <img src="images/{{ project.image }}" class="icon">
    <h3>{{ project.name }}</h3>
    {{ project.content | markdownify }}
    <p>&nbsp;</p>
  </div>
</div>
{% endfor %}
