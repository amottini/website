+++
date = "2012-01-27T10:32:41+01:00"
title = "Axon Extraction from Fluorescent Confocal Microscopy Images"
highlight = true
math = false
external_link = ""
summary = ""
tags = ["image_processing"]
image = ""
image_preview = "axon_ext_prev.jpg"

+++
<p style='text-align: justify;'>
The morphological analysis of axonal trees is an important problem in
neuroscience. The first step for such an analysis is the extraction of
the axon. Due to the high volume of generated image data and the
tortuous nature of the axons,manual processing is not feasible.
Therefore, it is necessary to develop techniques for the automatic
extraction of the neuronal structures. In this paper we present a new
approach for the automatic extraction of axons from fluorescent confocal
microscopy images. It combines algorithms for filament enhancement,
binarization,skeletonization and gap filling in a pipeline capable of
extracting the axons. The performance of the proposed method was
evaluated on real images. Results support the potential use of this
technique in helping biologists perform automatic extraction of axons
from fluorescent confocal microscopy images.
</p>



<figure>
    <img src="/img/segmentation_axon.jpg" alt="segmentation" width="65%" height="65%">
    <figcaption>
        <h4>Comparison between original image (left), our result (middle) and ground truth (right)
for two images (maximum intensity projections).</h4>
    </figcaption> 
</figure>


<figure>
<div class="main_block">
    <div class="inner_block">
        <img src="/img/MAX_normal_1.jpg" alt="normal axon" style="width: 350px; height: 350px;">
    </div>

    <div class="inner_block">
        <img src="/img/movie_binFIXED.gif" alt="reconstruction" style="width: 350px; height: 350px;">
    </div>    
</div>
<figcaption>
        <h4>Original maximum intensity projection image of a normal axon (left)
and extracted axon in 3D (right).</h4>
    </figcaption> 
</figure>