# PyBer_Analysis
Visualizing Ride-Sharing Data using Python and Pandas with Matplotlib in Jupyter Notebook

## Resources:
- Python 3.7.10 
- Anaconda 
- Pandas
- Matplotlib.pyplot 
- Jupyter Notebook

## Overview
- In this project we performed an exploratory analysis of Pyber ride sharing data in order to gain any insights into ridership and fare metrics by the types of cities in which Pyber operates. The goal for this analysis is to utilize insights from the ride sharing data to identify any potential correlation between a specific market type and total ride/fare revenue generated in the respective markets. In order to better illustrate the correlation between these key metrics we created visualizations that show the variance in performance by city type: rural, suburban, urban;  which can also be utilized by the executive team to improve access to ride-sharing and determine affordability in underserved areas. 

## Results
- Once we cleaned and merged the data together, we were able to identify some key insights that reaffirm baseline expectations for ride-sharing. The further you get from city centers the less accessible ride-sharing services become. The analysis results indicate that rural cities had the lowest number of rides, totalling **125 rides**; Suburban cities had more rides than urban areas with **625 rides**; and Urban cities had the highest ride volume with **1,625 rides**. The data also suggests that the costs of ride-sharing increases as the distance from the city center increases, which also impacts the number of Total Riders per city type and its accessibility as only **78 people used ride-sharing services in Rural areas as compared to Urban areas with a total of 2,405.** The results of the analysis can be referenced in the table below: 

![Pyber_analysis_summary_df_screenshot](https://github.com/Jflux05/PyBer_Analysis/blob/14d52f2cfe5207c3183adc03c40dace94952f2c7/analysis/Pyber_analysis_summary_df.png)

### Key Take Aways:
- Urban cities have the highest number of drivers, rides and total fares.
  - Although the Urban cities command the most drivers, rides and fares they have the lowest average fare per ride and fare per driver.
- Urban cities have the highest ridership demand while Rural cities have the lowest.
- Urban cities have 4x+ more drivers than Suburban cities.

- Suburban cities are in the middle having the 2nd most drivers, rides and total fares.
- Suburban cities have 6x + drivers than rural with almost 4.5x the revenue.


- Rural cities have the least amount of drivers, rides and total fares.
- Rural cities have the highest average fare per ride and driver.
  - Although Rural cities see the lowest number of drivers, rides & fares;  they have the highest average fare per ride and fare per driver.





- **We can make these insights from the data much easiert to understand and deduce by creating a multi-line line chart (see below), that shows the disparity and correlations of ride-sharing services across the three different city types, and it clearly demonstrates what are most likely accessibility-influenced trends.** 

![pyber_analysis-fig7](https://github.com/Jflux05/PyBer_Analysis/blob/cad5e1673df19c52716426d21a441f4872e06d57/analysis/Fig7.png)


## Summary

In our exploratory analysis, we were able to extract insights from the data which enabled us to identify an inverse correlation between average fare per ride and total rides taken. The results from our analysis indicate that the total revenue from fares for the Rural and Suburban markets are considerably lower than in the Urban markets.However, the impact of total fare price on customer demand for the service is not completely clear. In order to make ride-sharing more accessible across the various city types, Pyber needs to address the available supply of for each city type, increase reliability by ensuring timely service and consistent fare rates,  and further investigate market forces causing spikes in the fares across all three city types (like we saw in late Feb. 2019) and then leverage those insights in a manner where it could benefit Pyber’s business as a whole. My recommendations for Pyber to take advantage of the analysis results and drive revenue are to:

- Establish incentives for drivers in Urban cities to take more trips outside of the urban core, in Suburban and Rural areas to alleviate the supply issues outside of the urban core area. The increase in driver supply in the Suburban and Rural areas should reduce overall fare costs in these areas, which could act as an incentive for riders in these areas to utilize the service more often, thus driving more revenue for the ride sharing service.. 
  - Additionally, by reducing the supply of drivers in Urban cities, it has potential to increase total fare costs in the Urban city type, as a result of increased demand, which would drive additional revenue to an already top performing city type. 
- Create fare consistency and reliability (trip duration, wait time, and reduced fares). Thus, Pyber should increase its targeted advertising/marketing campaigns in these areas to onboard new drivers to address the supply issue, while simultaneously increasing rider awareness of the service to continue driving rider demand for the service. Which should offset the increased costs associated with marketing/advertising. 
- Pyber should start collecting total distance and weather condition data, to better understand what drives spikes in their services. If they can identify what factors attributed to the spike witnessed in late February, there is the possibility the data provides insights on how Pyber could intentionally increase demand, while addressing the driver supply issues, thus establishing a service that maximizes it revenue potential while meeting rider and market expectations and an accessible, reliable, and efficient ride-sharing service. 

As Pyber considers its options to improving its service and driving revenue, it’s important for the company to keep these observations in mind when deciding how to improve affordability and access.

