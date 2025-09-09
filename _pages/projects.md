---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 3
horizontal: true
---

<!--
<!-- pages/projects.md --!>
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
--!>

This page provides a brief overview of the various projects I completed as part of my coursework, extracurricular activities, and personal interests purely driven by curiosity. I thoroughly enjoyed my time at Team Anveshak at IIT Madras, where I made significant contributions. I developed my own solver from scratch for the lid-driven cavity problem for my Computational Fluid Dynamics (CFD) course. This experience, in particular, paired with my interest in mechanical design optimization, sparked my interest in computational engineering.

---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/matDes_graphAbs.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
     Mechanical design optimization and fabrication of Mars rovers @ Team Anveshak, IIT Madras
</div>

---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/vfmPaper_GrapAbs.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Estimating correlation between SLM powder spreading direction and particle anisotropy @ Mechanics of Materials Lab, IIT Madras
</div>

---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/cloakPaper_DIC.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   A CFD solver to simulate the benchmark 2D lid-driven cavity flow problem for the Foundations of CFD course (Prof. Arul Prakash, Applied Mechanics, IIT Madras).
</div>

---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/cloakPaper_DIC.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Summer 2024 internship @ Jindal Stainless Ltd, Odisha, India: study and prediction of steel melting shop defects in Ti-stabilized stainless steel coils.
</div>

---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/cloakPaper_DIC.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    3D convex hull construction using the gift wrapping algorithm for the course on data structures and algorithms (Prof. BSV Prasad Patnaik, Applied Mechanics, IIT Madras).
</div>

---
