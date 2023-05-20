---
layout: page
title: Designing digital to analog converter (DAC) and Analog to digital converter (ADC) using Cadence
description: 
img: assets/img/adc1.png
importance: 5
category: Research
---
<div style="text-align: justify;
        text-justify: auto;">
For the 10-bit current steering DAC, it is necessary to create the corresponding digital code. To do this, first, a sinusoidal signal was created with the help of MATLAB software. Then it was sampled and quantized, and finally, it was converted into binary values. Separate files were used as vpwl input.
The current source and the reconstructed filter schematics are shown below:

</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/adc1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Schematic
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/adc2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Schematic
</div>

For the 5-bit Flash ADC, to create different voltages, a resistor ladder was used as depicted below:


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/adc3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Resistor ladder
</div>

To compare voltages, a comparator circuit was designed:

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/adc4.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Comparator circuit
</div>
