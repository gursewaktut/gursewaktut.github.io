---
layout: page
title: Atreus Keyboard
description: column-staggered travel keyboard design
img: assets/img/finished_build.jpeg
importance: 1
category: fun
related_publications: 
---

Atreus is an ergonomic 40% mechanical keyboard. The design is available at [Atreus Keyboard](https://gitlab.com/technomancy/atreus) and it is entirely opensource. The original design uses Matias Quiet Click switches and Arduino Pro Micro for handwired build and A-star micro microcontroller for pcb build.

The firmware used for the original design is QMK. For my build, I have deviated slightly from this above design. For the microcontroller, I am using a raspberry pi pico which is just \$6 compared to \$20 for pro-micro. I am also using KMK firmware which is also opensource and it runs on circuit python which is used to write code for with Pi Pico.

Below is the list of parts I used:

- [50 Matias Quiet Click Switches](https://matias.store/products/matias-quiet-click-switch-box-of-200)
- [Full set of Matias Alps Keycaps](https://matias.store/products/keycap-set-white-blank)
- [Raspberry pi pico from Canakit](https://www.canakit.com/raspberry-pi-pico-w.html)
- 50 1N4148 diodes from ebay
- [Case material and laser cutting from Laser Cutter Cafe, Vancouver](http://www.lasercuttercafe.com/)
- USB micro cable, get anywhere
- A soldering iron.

The whole thing cost me around \$200. At the time of writing this post, the prices of the switches and keycaps seems to have increased by $20 each. But the switches and the keycaps can be replaced by cherry style switches and keycaps.
The laser cutting cost me around \$55. The majority of the cost goes to switches, keycaps and case. The rest of the parts are relatively cheap.

For soldering, you can get away with cheap soldering iron but it is recomended to get a soldering iron that can be temperature controlled.

I put everything together using machined screws.


The instructions for assembly, files for case and the QMK firmware can be found at the gitlab repository mentioned above. The layout for KMK firmware code that I used can be found at [Layout](https://github.com/gursewaktut/atreus_kmk).


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/pi_pico_rot.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/pi_pico_soldered.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/columns_rows.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/finished_build.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>



