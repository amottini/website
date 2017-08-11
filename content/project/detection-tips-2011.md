+++
date = "2011-03-01T10:32:45+01:00"
external_link = ""
highlight = true
math = false
image = ""
image_preview = "detection_tips_prev.jpg"
summary = ""
tags = ["image_processing"]#"Bi-photon Microscopy","Marked Point Process"
title = "Detection and Tracking of Axonal Tips from Bi-Photon Microscopy Images"

+++

<p style='text-align: justify;'>
Live cell two-photon microscopy is an effective tool for the analysis of dynamical
processes occurring in living samples. This technique,when combined
with fuorescence, allows the detection of objects of interest in 3D
space and time.  Due to the high volume of data, the automatic
analysis of the images is desired. To this end, the Marked Point Process
(MPP) detection framework was selected. MPP is a probabilistic framework
which has been successfully applied to the detection of objects in
different image processing applications. Its main advantages are that
the number of objects to be detected can be unknown, and that geometric
constraints on the objects can be easily modeled. As a first
approximation, we proposed a 3D MPP model of spheres to extract the
axonal extremities. We define a prior energy designed to penalizes (but
not forbid) overlaps, and a data energy based on the Bhattacharya
distance between the distributions. Once the energy function has been
defined, the issue is to find the configuration U(X) that minimizes it.
Due to the intricate nature of U(x), usual minimization algorithms
cannot be applied. Therefore, we have chosen Multiple Births and Deaths
(MBD). The method was evaluated on a set of real 3D+t images. Although
results show there is still work to be than in this area, they suggest
this approach could be appropriate for solving the extraction problem
</p>

<figure>
    <img src="/img/film_axonCORTO.gif" alt="bi-photon image" width="35%" height="35%">
    <figcaption>
        <h4>Dynamic 3D+time image sequences of developing neurons.</h4>
    </figcaption> 
</figure>

<figure>
    <img src="/img/evol1b.jpg" alt="tracking">
    <figcaption>
        <h4>Tracking result for four consecutive frames (left to right).</h4>
    </figcaption> 
</figure>