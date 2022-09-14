# Project Name
Bike sharing predictive analysis based on multiple linear regression

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

Problem statement:
BoomBikes wants to know the following
- Predictors for the demand of shared bikes
- How well these predictors describe the demand
- Model the demand to understand the potential demands in new market

Dataset inforation: 
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors
day.csv dataset is being used

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Both manual feature elimination and RFE approach tried and below are the conclusion
- Year has a possitive impact on the number of bike users. This means that business can generally increase the number of bikes offered to customers provided all the other parameters are similar as the data in the gived data set
- Working day has +ve impact conversly holiday has negative impact 
- Temperature/felt temperature have positive impact.
- humidity have negative impact
- windspeed have negarive impact
- summer and winter have positive impact or conversly spring have negative impact 
- More bikes are used in the month of august and september compared to other months
- Clear weather has positive impact

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python ver 3.9.12
- pandas ver 1.4.2
- matplotlib ver 3.5.1
- seaborn ver 0.11.2
- sklearn ver 1.0.2
- statsmodel 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

## Contact
Created by [@vivekprahlada] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
