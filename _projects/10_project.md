---
layout: page
title: Software for Optical Character Recognition (OCR)
description: 
img: assets/img/19.jpg
importance: 3
category: Other
---

I implemented a commercial program to extract text information from catalogs. I used OpenCV to extract regions of interest and preprocess images. First, I used adaptive thresholding to separate desirable foreground image objects from the background. Next, I used a series of morphological transformations, such as the opening to detect horizontal and vertical lines. Finally, I used tesseract for OCR.



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ocr.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Application GUI
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/18jpg.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/18.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Image preprocessing to extract region of interest. 
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/19.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Generating output using tesseract.
</div>

