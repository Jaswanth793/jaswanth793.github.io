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
Welcome! My current research work focuses on the design of architected materials that are tailored for multi-purpose applications rather than the traditional approach of single-purpose design. Few research works available in the literature investigate the possibility of optimizing/designing a structure for multiple applications, but these applications in turn have been within the same phenomenon. For example, optimizing a lattice structure for a lower initial peak stress but higher overall energy absorption. Both of these properties, although different, are governed by the mechanical properties of the material. My interest, however, is to explore the possibility of uncovering lattice structure designs that perform well both mechanically and thermally as crash absorbers and thermal dissipators, respectively. Such lattices can be trivial in the case of automobiles, where they can be adapted to replace radiator fins, thereby passively dissipating heat and absorbing crashes with minimal coolant leakage when such events occur, or even as an enclosure for automotive power electronics or battery packs in the case of EVs.

---

##### Ongoing research (master's thesis):
    
Multi-objective optimization of functionally graded BCC lattices for crashworthiness and thermal dissipation: The final optimized lattice achieved a 115% improvement in energy absorbed per unit mass with a 36% reduction in the initial peak stress experienced at the distal end during impact, compared to a ground lattice of the same relative density but with struts of uniform diameter. The optimized lattice also exhibited a 31% reduction in pressure drop for the same amount of heat transferred as compared to the  ground lattice, thereby requiring less power to push air through the pores during forced convection.

---

##### Undergraduate research 2b:

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
    Biomimetic hierarchical auxetic honeycomb cells for impact absorption: Auxetic honeycomb cells were given a uniform and a non-uniform stochastic Voronoi distribution within their cell walls. The cells with a non-uniform Voronoi distribution had a dense network in the walls perpendicular to the loading direction and a coarse network in the walls parallel to the loading direction, thereby maintaining a similar mass as the uniform cell. It was hypothesised that an intricate Voronoi distribution at the stress-intense regions (similar to the trabecular bone of the human body) would result in a higher plastic energy absorbed than the cell with a uniform Voronoi distribution. The simulation results indicated that the auxetic cell with a non-uniform Voronoi structure absorbed nearly twice as much energy per unit mass at lower impact velocities compared to the uniform auxetic cell, particularly during the phase just before densification. At higher velocities, both cell types absorbed similar amounts of energy up to densification. This can be attributed to the complete deformation of the Voronoi cells located within the walls perpendicular and parallel to the impact direction at higher impact directions, hence nullifying our hypothesis. However, this doesn't happen at lower impact velocities. Thus, the hypothesis was found to be valid at lower velocities.
</div>

---

##### Undergraduate research 2a:

<div class="rounded z-depth-1 mb-3">
  <video controls preload="metadata" class="w-100">
    <source src="{{ '/assets/video/Regular_vs_auxetic_crush.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>
<div class="caption">
    During my initial days at the Mechanics of Materials Lab @ IIT Madras, I tried to learn and explore various geometries that produced vastly different impact absorption behaviours. Here, for example, I found out that auxetic honeycomb structures with a negative Poisson's ratio outperform the regular honeycomb structures. This was due to the higher degree of densification in the auxetic structures than in the honeycomb structures, even during the impact.
</div>

<div class="rounded z-depth-1 mb-3">
  <video controls preload="metadata" class="w-100">
    <source src="{{ '/assets/video/multi_material_crush.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>
<div class="caption">
    I also explored multi-material honeycomb structures with different materials, with a stark difference in Young's modulus and yield strength, which were modelled at different zones of the honeycomb structure. The first honeycomb structure shown here was modelled with the properties of Ti-6Al-4V throughout its width. The second honeycomb structure, on the other hand, was modelled with an Al6061 sectioned between a Ti-6Al-4V section on the impact end and a Ni section on the fixed end. The deformation pattern is very different in these structures, showing a premature deformation in the Al6061-Ni interface (due to the lower yield strength of Ni), which is beneficial when a lower stress at the fixed end is the goal.
</div>

---

##### Undergraduate research 1:

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/hess.jpg"  title="HESS" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Design and Development of an electro-mechanical testbed for a Hybrid Energy Storage (HES) system: A real-life electro-mechanical EV testbed was designed and fabricated to test hybrid setups of batteries and supercapacitors (in-house made active-carbon based). Remote monitoring of real-time sensor data was implemented using an ESP32 microcontroller. Multiple load profiles were made to replicate real driving scenarios for stress testing the HES system. The tesbed was later found useful to measure much higher capacitances (from the discharge profiles) of supercapacitors, which wasn't possible with conventional LCR meters.
</div>

---
