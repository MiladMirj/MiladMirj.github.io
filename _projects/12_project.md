---
layout: page
title: Persian Text Detection using Wikipedia persian
description: 
img: assets/img/train_batch0.jpg
importance: 2
category: Research
---


<h3><a href="https://github.com/MiladMirj/Wikipedia-fa-Articles-Extractor-with-Text-Detection">GitHub page !</a></h3>

<div style="text-align: justify;
        text-justify: auto;">
In the initial phase of this project, I aim to create an article scraper for Wikipedia in Persian. It will start from a random URL, extract all links on that page, then randomly open another page and repeat the process. Next, I aim to overlay text on different random images. Depending on the length of the text, I will break it into smaller chunks, and for each chunk, I will create images using a random font and draw the text at a random position on the image. I also create augmented images for better performance. Using a YOLO v5 model, The model will then take an image as input, with up to four possible locations of text and their bounding boxes. The model's output will be the number of detected bounding boxes and their coordinates. It was trained for maximum 4 text areas inside an image.

</div>



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/train_batch2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/train_batch1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/val_batch0_labels.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Capture2.JPG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Capture.JPG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Some labels and prediction
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
