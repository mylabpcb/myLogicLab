---
title: "myLogic: Positive EDGE Detector"
subtitle: A positive EDGE detector gate built with 12 CMOS transistors
layout: page
show_sidebar: false
hide_footer: true
hide_hero: false
hero_height: hero-minHeigth
hero_darken: false
---
> The content is under development, the final version will be as soon as possible.

This module is a positive EDGE detector based on a 3 NOT gates for delay and an AND gate, between the first and second NOT gate it inserted and additional RC delay circuit. NOT gates are too fast and the duration of the edge is too small to trigger modules based on BSS84 and 2N7002.
<br/>
<figure class="center">
    <img src="{{ site.baseurl }}/img/modules/myLogic_pos_edge_min.png" alt="Positive EDGE module" title="Positive EDGE  module" width="500px">
    <figcaption>Positive EDGE module</figcaption>
</figure>
<figure class="center">
    <img src="{{ site.baseurl }}/img/modules/sch/myLogic_pos_edge_sch_min.png" alt="Positive EDGE  schematic" title="Positive EDGE schematic" width="600px">
    <figcaption>Positive EDGE schematic</figcaption>
</figure>
