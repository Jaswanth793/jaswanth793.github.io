---
layout: page
permalink: /research/
title: Research
description:
nav: true
nav_order: 2
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/summary_research.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---

#### Summary
Welcome! My research focuses on designing architected materials for multi-purpose applications, departing from traditional single-purpose designs. While some studies have examined optimization for multiple functions, they often concentrate on single phenomena, such as reducing initial peak stress while maximizing energy absorption. Although the material properties are important, the overall response is mainly determined by the lattice architecture, including cell topology, relative density, and strut geometry.

My goal is to explore lattice structure designs that perform well mechanically and thermally, acting as effective crash absorbers and thermal dissipators. The focus is on identifying designs that excel in both functions, which could be particularly valuable in the automotive industry. These structures might replace radiator fins to dissipate heat and absorb impacts during crashes, reducing coolant leakage, and could also serve as enclosures for power electronics or battery packs in electric vehicles (EVs).

---

##### Ongoing research (master's thesis): Multi-objective optimization of functionally graded BCC lattices for crashworthiness and thermal dissipation
    
The final optimized lattice achieved a 115% improvement in energy absorbed per unit mass with a 36% reduction in the initial peak stress experienced at the distal end during impact, compared to a ground lattice of the same relative density but with struts of uniform diameter. The optimized lattice also exhibited a 31% reduction in pressure drop for the same amount of heat transferred as compared to the  ground lattice, thereby requiring less power to push air through the pores during forced convection.

---

##### Undergraduate research 2b: Biomimetic hierarchical auxetic honeycomb cells for impact absorption

<div class="rounded z-depth-1 mb-3">
  <video controls preload="metadata" class="w-100">
    <source src="{{ '/assets/video/voronoi.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/voronoi_plot.jpg" title="Heirarchical auxetic cells under impact" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Auxetic honeycomb cells were designed with both uniform and non-uniform Voronoi distributions in their walls. The non-uniform cells featured a dense network in walls perpendicular to the loading direction and a coarser network parallel to it, maintaining similar mass to the uniform cells. It was hypothesized that this intricate distribution (similar to the human trabecular bone) would absorb more energy at stress concentration regions, similar to trabecular bone. Simulation results showed that at lower impact velocities, the non-uniform Voronoi auxetic cell absorbed nearly twice the energy per unit mass compared to the uniform cell. However, at higher impact velocities, both types absorbed similar energy due to complete deformation of the Voronoi cells, thus confirming that the hypothesis only applies at lower velocities.
</div>

---

##### Undergraduate research 2a: Auxetic/regular Honeycombs and multi-material honeycombs

<div class="rounded z-depth-1 mb-3">
  <video controls preload="metadata" class="w-100">
    <source src="{{ '/assets/video/Regular_vs_auxetic_crush.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>
<div class="caption">
    During my initial days at the Mechanics of Materials Lab @ IIT Madras, I tried to learn and explore various geometries that produced vastly different impact absorption behaviours. Here, I found out that auxetic honeycomb structures with a negative Poisson's ratio outperform the regular honeycomb structures. This was due to the higher degree of densification (at the impact front during the impact) in the auxetic structure than in the honeycomb structure.
</div>

<div class="rounded z-depth-1 mb-3">
  <video controls preload="metadata" class="w-100">
    <source src="{{ '/assets/video/multi-material_crush.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>
<div class="caption">
    I also explored multi-material honeycomb structures with different materials, with a stark difference in Young's modulus and yield strength, which were modelled at different zones of the honeycomb structure. The first honeycomb structure shown here was modelled with the properties of Ti-6Al-4V throughout its width. The second honeycomb structure, on the other hand, was modelled with a section of Al6061 sandwiched between a Ti-6Al-4V section on the impact end and a Ni section on the fixed end. The deformation pattern is very different in the second structure, showing a premature deformation in the Al6061-Ni interface (due to the lower yield strength of Ni), which is beneficial when lower stress at the fixed end is the design goal.
</div>

---

##### Undergraduate research 1: Design and Development of an electro-mechanical testbed for a Hybrid Energy Storage (HES) system

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/hess.jpg"  title="HESS" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A real-life electro-mechanical EV testbed was designed and fabricated to test hybrid setups of batteries and supercapacitors (in-house-made active-carbon-based). Remote monitoring of real-time sensor data was implemented using an ESP32 microcontroller. Multiple load profiles were made to replicate real driving scenarios for stress testing the HES system. The tesbed was later found useful to measure much higher capacitances (from the discharge profiles) of supercapacitors, which wasn't possible with conventional LCR meters.
</div>

---
