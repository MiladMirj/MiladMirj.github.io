---
layout: page
title: Block matching motion estimation
description: 
img: assets/img/block1.png
importance: 1
category: Research
---

<div style="text-align: justify;
        text-justify: auto;">
Block matching motion estimation is one of the methods of motion estimation in video frames. For performing block matching motion estimation, the current frame is divided into a number of non-overlapping blocks with specific sizes and by doing a search for each created block, the most similar block to that candidate block in the reference frame is selected. The ultimate goal is to report a motion vector that shows the amount of block displacement in two consecutive images. The purpose of this study is to provide an algorithm for block matching motion estimation with minimum error and high speed. In the first step of implementing this algorithm, a brand new and efficient method for automatically generating blocks with different shapes and sizes according to the identified location and direction of movement is designed. Three shapes: square, horizontal and vertical rectangles, are the available options. Next, by utilizing adaptive searching tools, such as the search window size selection, global motion compensation, and changing reference frame, it is attempted to decrease the computation load imposed on the system while maintaining the quality of motion estimation; therefore, after implementing each phase of the algorithm, its performance is compared with the previous stage. Finally, by introducing two patterns for scanning the blocks in the search window, the final result of this study is presented in two general categories of quality and efficiency.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tenniscol_generated2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tennisdiag_generated2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tennisrow_generated2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Three possible block structures
</div>



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/hall_frame50.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/hall_mask50.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/hall_static_all50.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Generating blocks
</div>



<!-- 
The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<!-- <div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div> --> 

{% endraw %}
