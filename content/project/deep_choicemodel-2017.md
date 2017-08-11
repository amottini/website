+++
date = "2017-02-15T10:32:45+01:00"
external_link = ""
highlight = true
math = false
image = ""
image_preview = "pointer2.jpg"
summary = ""
tags = ["deep-learning","machine_learning"]
title = "Deep Choice Model Using Pointer Networks for Airline Itinerary Prediction"

+++

<p style='text-align: justify;'>
Travel providers such as  airlines and on-line travel agents are becoming more and more interested in understanding how passengers choose among
alternative itineraries when searching for flights. This knowledge helps them better display and adapt their offer, taking into account market 
conditions and customer needs. Some common applications are not only filtering and sorting alternatives, but also changing certain attributes in 
real-time (e.g., changing the price). In this paper, we concentrate with the problem of modeling air passenger choices of flight itineraries. This 
problem  has historically been tackled using classical Discrete Choice Modelling techniques. Traditional statistical approaches, in particular the 
Multinomial Logit model (MNL), is widely used in industrial applications due to its simplicity and general good performance.  However, MNL models 
present several shortcomings and assumptions that might not hold in real applications. To overcome these difficulties, we present a new choice model 
based on Pointer Networks. Given an input sequence, this type of deep neural architecture combines Recurrent Neural Networks with the Attention Mechanism 
to learn the conditional probability of an output whose values correspond to positions in an input sequence. Therefore, given a sequence of different 
alternatives presented to a customer, the model can learn to point to the one most likely to be chosen by the customer. The proposed method was evaluated 
on a real dataset that combines on-line user search logs and airline flight bookings. Experimental results show that the proposed model outperforms the 
traditional MNL model on several metrics.
</p>

<figure>
    <img src="/img/pointer2.jpg" alt="deep choice model diagram">
    <figcaption>
        <h4>Proposed deep choice model using pointer network (encoder in green, decoder in blue, normalization in orange and embedding in purple).</h4>
    </figcaption> 
</figure>


<figure>
    <img src="/img/top_N_accV3.jpg" alt="top-N acc. for tested methods">
    <figcaption>
        <h4>top-N accuracy for the compared methods.</h4>
    </figcaption> 
</figure>

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/iyqh7mPrhFc?list=PLliTSxmRFGVPkvUZb3Q-DzvOgs20LOinA" frameborder="0" allowfullscreen></iframe>
</p>

