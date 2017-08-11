+++
date = "2016-01-27T10:28:06+01:00"
title = "Relative Label Encoding for the Prediction of Airline Passenger Nationality"
image = ""
summary = ""
tags = ["machine_learning"]
math = false
external_link = ""
image_preview = "label_prev.jpg"
highlight = true

+++
<p style='text-align: justify;'>
In the airline industry, a Passenger Name Record (PNR) stores the travel itinerary of an individual or group of passengers travelling together. 
A PNR always contains all the flight information regarding each segment of a journey, and may contain additional important information such as nationality, gender and age of the passengers. From a commercial point of view, these passenger attributes are of particular interest to all actors in the travel industry (e.g., airlines and airports).  However, on average, only ten percent of PNR records have this information. Therefore, their prediction is of great interest. 
In this study we propose a methodology to predict the nationality of passengers based on PNR data. To avoid having to solve a classification problem with 195 classes, most of which will not be well represented in the data, we take advantage of a peculiarity of this data. In most cases, the nationality of a passenger will match the value of one or more of the other PNR attributes. Therefore, we can encode the target variable by transforming the nationality country code into the index of the feature it matches (e.g., country of origin or destination of the trip). 
The relative encoding of the target variable allows us to simplify the original problem significantly, while obtaining better classification accuracy.
Since the new classes are non-exclusive, the problem falls in the  multi-label classification paradigm.  
The proposed methodology was tested on PNR data of passengers passing through an important European airport, which handles more than twenty million passengers per year. The model performance was evaluated using three indicators. Results  show that we are able to predict the nationalities with good accuracy, and outperform both a  classical multi-class methodology and a ad-hoc rule-based algorithm used in the industry. 
</p>





<figure>
    <img src="/img/pnr_ex.jpg" alt="segmentation" width="45%" height="45%">
    <figcaption>
        <h4>Example of a PNR (illustrative example with fictitious data).</h4>
    </figcaption> 
</figure>



<figure>
    <img src="/img/topNat15V2.jpg" alt="segmentation" width="45%" height="45%">
    <figcaption>
        <h4>Predicted number of passengers (in log scale) per nationality for each of the three methods, comparison with ground truth (the countries have been anonymized and ordered by number of passengers).</h4>
    </figcaption> 
</figure>


<figure>
    <img src="/img/weighterError.jpg" alt="segmentation" width="45%" height="45%">
    <figcaption>
        <h4>Weighted error for the three compared methods.</h4>
    </figcaption> 
</figure>
