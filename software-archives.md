---
layout: default
title: Software Archives
---

*This page lists most software I have developed as an independent in the past, but which are not distributed anymore (freeware, shareware or commercial licenses). For software developed while working at companies, see the full list on the right side.*

<p>&nbsp;</p>
{% for project in site.software_archives %}
<div class="row">
  <div class="col-md-12">
    <img src="images/{{ project.image }}" class="icon">
    <h3>{{ project.name }} ({{ project.release }})</h3>
    {{ project.content | markdownify }}
    <p>&nbsp;</p>
  </div>
</div>
{% endfor %}
