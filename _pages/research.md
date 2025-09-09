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
        {% include figure.liquid path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---

#### Summary
Welcome! My current research work focuses on the design of architected materials that are tailored for multi-purpose applications rather than the traditional approach of single-purpose design. Few research works available in the literature investigate the possibility of optimizing/designing a structure for multiple applications, but these applications in turn have been within the same phenomenon. For example, optimizing a lattice structure for a lower initial peak stress but higher overall energy absorption. Both of these properties, although different, are governed by the mechanical properties of the material. My interest, however, is to explore the possibility of optimizing/discovering lattice structures that perform well both mechanically and thermally as crash absorbers and thermal dissipators, respectively. Such lattices can be trivial in the case of automobiles, where they can be adapted to replace radiator fins, thereby passively dissipating heat and absorbing crashes with minimal coolant leakage when such events occur.

---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
     Multi-objective optimization of functionally graded BCC lattices for crashworthiness and thermal dissipation: A structured framework for identifying designs, running simulations to feed surrogate models and finally, using goal programming for multi-objective optimization is presented.
</div>

---

<div class="img-fluid rounded z-depth-1 mb-3">
  <video controls preload="metadata" width="100%">
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

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/hess.jpg"  title="HESS" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Design and Development of an electro-mechanical testbed for a Hybrid Energy Storage (HES) system: A real-life electro-mechanical EV testbed was designed and fabricated to test hybrid setups of batteries and supercapacitors (in-house made active-carbon based). Remote monitoring of real-time sensor data was implemented using an ESP32 microcontroller. Multiple load profiles were made to replicate real driving scenarios for stress testing the HES system. The tesbed was later found useful to measure much higher capacitances (from the discharge profiles) of supercapacitors, which wasn't possible with conventional LCR meters.
</div>

---
