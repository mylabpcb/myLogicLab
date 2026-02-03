---
title: "myLogic: Negative EDGE Detector"
subtitle: A Negative EDGE detector gate built with 10 CMOS transistors
layout: page
show_sidebar: false
hide_footer: true
hide_hero: false
hero_height: hero-minHeigth
hero_darken: false
---
> The content is under development, the final version will be as soon as possible.

This module is a negative EDGE detector based on a 3 NOT gates for delay and a NAND gate, between the first and second NOT gate it inserted and additional RC delay circuit. NOT gates are too fast and the duration of the edge is too small to trigger modules based on BSS84 and 2N7002.
<br/>
<figure class="center">
    <img src="{{ site.baseurl }}/img/modules/myLogic_neg_edge_min.png" alt="Negative EDGE module" title="Negative EDGE  module" width="500px">
    <figcaption>Negative EDGE module</figcaption>
</figure>
<figure class="center">
    <img src="{{ site.baseurl }}/img/modules/sch/myLogic_neg_edge_sch_min.png" alt="Negative EDGE  schematic" title="Negative EDGE schematic" width="600px">
    <figcaption>Negative EDGE schematic</figcaption>
</figure>
