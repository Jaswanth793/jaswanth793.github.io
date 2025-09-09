---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 3
horizontal: true
---

<!-- pages/projects.md -->
<div class="projects">

  {% assign sorted_projects = site.projects | sort: "importance" %}

  {% if page.horizontal %}
  <div class="row row-cols-1">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
  </div>
  {% else %}
  <div class="row row-cols-1">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}

</div>
