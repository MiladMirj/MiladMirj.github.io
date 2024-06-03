---
layout: page
title: RGB to gray scale converter and Gaussian blur filter using VHDL
description: 
img: assets/img/2.jpg
importance: 3
category: Research
---

The overall schematic is shown below. First, image pixels are fed into the input block using a text file. The next block calculates the weighted sum of pixels values, and finally, a Gaussian filter is applied to the image. The outputs are then stored in a text file.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/test3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/gray.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/blur.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Generated outputs
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Schematic 
</div>






