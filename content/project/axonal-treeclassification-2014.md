+++
external_link = ""
date = "2014-01-27T10:32:33+01:00"
summary = ""
highlight = true
image = ""
title = "Axonal Tree Classification Using an Elastic Shape Analysis Based Distance"
image_preview = "mean_shape_prev.jpg"
tags = ["machine_learning","image_processing"]
math = false

+++
<p style='text-align: justify;'>
The analysis of the morphological differences between normal and
pathological neuronal structures is of paramount importance. Some
methods for the comparison of axonal trees only take into account
topological information (such as TED), while others also include
geometrical information (such as Path2Path). In a previous work, we have
presented a new method for comparing tree-like shapes based on the
Elastic Shape Analysis Framework (ESA). In this paper, we extend this
method by computing the mean shape of a population. Moreover, we propose
to evaluate and compare these 3 approaches (TED, Path2Path and ESA) with
a classification scheme based on feature computation and K-means.
We evaluate these approaches on a database of 44 real 3D
confocal microscopy images of two populations of neurons. Results show
that the proposed method distinguishes better between the two
populations.</p>


<figure>
    <img src="/img/mean_shape_procedure.jpg" alt="mean shape procedure">
    <figcaption>
        <h4>Calculation of mean shape of a set of tree shapes.</h4>
    </figcaption> 
</figure>





<figure>
<div class="main_block">
    <div class="inner_block">
        <img src="/img/normal/MAX_3.jpg" style="width: 200px; height: 200px;" alt="normal1">
    </div>

    <div class="inner_block">
        <img src="/img/normal/MAX_5.jpg" style="width: 200px; height: 200px;" alt="normal2">
    </div>    
	
	<div class="inner_block">
        <img src="/img/normal/MAX_6.jpg" style="width: 200px; height: 200px;" alt="normal3">
    </div>    
</div>

<div class="main_block">
    <div class="inner_block">
        <img src="/img/mutant/MAX_47.jpg" style="width: 200px; height: 200px;" alt="mutant1">
    </div>

    <div class="inner_block">
        <img src="/img/mutant/MAX_imp7_1GFP.jpg" style="width: 200px; height: 200px;" alt="mutant2">
    </div>    
	
	<div class="inner_block">
        <img src="/img/mutant/MAX_imp7_1GFP.jpg" style="width: 200px; height: 200px;" alt="mutant3">
    </div>    
</div>

<figcaption>
        <h4>Examples of axonal trees from the normal (top) and mutant
(bottom)populations (2D projections).</h4>
    </figcaption> 
</figure>




<figure>
    <img src="/img/mean_shapes.jpg" alt="mean shape">
    <figcaption>
        <h4>Mean normal (left) and mutant (right) axonal trees (2D projections).</h4>
    </figcaption> 
</figure>





