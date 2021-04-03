# PyBer_Analysis

## Overview of the analysis: Explain the purpose of the new analysis.

The CEO of PyBer, a ride-sharing company has tasked me and a partner, Omar, to provide an analysis of their ride-sharing data from CSVs. To do this, we will create a summary of ride-sharing data by city type (Urban, Suburban and Rural). Based on the differences in ride-sharing data between the city types, provide recommendations to decision makers at PyBer. 

## Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
**PyBer Summary DataFrame**
<img width="548" alt="PyBer-Summary_DF" src="https://user-images.githubusercontent.com/69849998/113494425-0d1e9980-94b6-11eb-9fab-7b1cf3c75eb2.png">

The summary dataframe above demonstrates that the Rural cities have the lowest total rides (125), drivers (78) and fares ($4,327.93), while urban the highest of total rides (1,625), drivers (2,405) and fares (39,854.38). while the avg fare per ride and per driver is the highest in rural at $34.62 and $55.49 respectively. It makes sense that Rural cities have the fewest rides and drivers and lowest fares, but the highest average fare per ride and per driver, since ride shares in rural ares are likely fewer and longer and more expensive since there are fewer drivers. This is based on the assumption, like Uber, that the lower the demand and number of drivers, the higher the cost.

![Fig8](https://user-images.githubusercontent.com/69849998/113494431-1b6cb580-94b6-11eb-84fc-41819bad17c4.png)

The line graph above demonstrates that Urban cities generated the most fares, Rural cities, the least, and suburban cities were in between. All three city types saw an uptick in fares in late February. 

## Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

* The average fare per driver is significantly lower  in urban cities ($16.57), compared to Suburban and Rural. To increase the fare per driver, one suggestion could simply be to increase the cost of the rides slightly. 
* Rural cities generate the highest fare per ride and per driver, however the total fares are quite low at $4,327.93 comparatively. To increase the total fares for rural cities, and assuming the demand is high, one suggestion could be to hire more drivers in these cities. 
* It would be interesting to explore the impact of the weather on the number rides for each city type. If there is an impact, a suggestion could be to incentivize drivers to work that day to ensure there is enough supply to meet the demand. 
