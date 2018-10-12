# disaster1.0

## Introduction:

A tropical cyclone is defined as an area of low pressure which develops over tropical or subtropical waters. It is also called as typhoon or hurricane in other parts of the world. 
 
A cyclone is characterized by warm temperatures, high humidity, wind and rainfall levels. Though there have been significant advancements in technology to predict the course of cyclones, yet they cannot be predicted with high accuracy as they can suddenly weaken or change their course. Moreover, the formation of cyclone can be only be known with certainty 24-48hrs before it strikes. This also leaves very less time for preparation and implementation of evacuation and other emergency plans. Hence, obtaining accurate predictions of the number of TCs (tropical cyclones), with lead times of at least 3 months or more, in an upcoming TC season is of vital importance for the preparation of emergency response services for the areas expected to be affected.
 
Considering all the above shortcomings, our team proposes to develop a system that uses historical data trends for training the model and current weather data to monitor all factors mentioned above(obtained from IMD satellite and radar sources), thereby improving the probability of predicting a cyclone as early as possible, track its path with better accuracy and analyse its impact based on its intensity. 

## Cyclone Prediction Algorithm:

The method that we will try to use is as follows:
The neural network technique we will be implementing is based on the three-layer back propagation, using predictors such as zonal wind, relative humidity etc. The model contains five neurons, corresponding to the five predictors, five neurons in the hidden layers and one neuron in the output layer, namely the seasonal number of tropical cyclones formed. After a bit of research we found that five hidden neurons produce the best result.

## Cyclone Management Features:

Due to the quick development of a cyclone, after the results of the prediction are obtained, all the areas which appeared in the result will be alerted. The users with our application installed will also receive an alert message. Then the process of management begins. 

We also plan to implement disaster management measures such as:

 -Including do’s and don’ts.
 
 -Providing details of nearby hospitals, police stations, next food drop points, relief camps displayed on a map.
 
 -Including an SOS feature, which sends a distress signal to all the nearby relief centers /police/ army.
 
 -Another feature which informs close friends and family about the status.
 
 -Regular updates on the situation in the locality will be sent.

It will include all the information, a person who is stranded in a cyclone would need to be aware of.

## Conclusion:

Our project will be implemented as an application on visual studio and will focus on cyclone as a whole. We have decided to stick to one disaster and pursue predicting and managing it, to the best of our abilities.
 

