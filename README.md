# An Analysis of Ride-Sharing Data by City Type

## Project Overview

### I will be looking at ride-sharing data and grouping it by city type; urban, suburban, and rural. I will use a variety of methods to do this: groupby() function with count() and sum() methods, loc, pivot(), resample(), and finally, plotting a line graph using the matplotlib.pyplot dependency.

## Results

The data show that the vast majority of rides occur in urban cities and that the vast majority of drivers work in urban cities, with the lowest number of rides and drivers occuring in rural cities. Conversely, the highest average fares occur in rural cities, with the lowest average fares occuring in urban cities. The data also show that there are less drivers in rural and suburban cities than there are rides, but there are far more drivers than rides in urban cities.

![Fare Summary DataFrame](https://github.com/NickBaldassarre/PyBer_Analysis/blob/61cedf89906deed37363ba5821625d621bec937d/analysis/summary_df.png)

The line chart shows that all three city types follow similar trends, likely impacted by things like weather or holidays. This illustrates that the relationship between the average fares in all three city types is consistent over time.

![Fare Summary](https://github.com/NickBaldassarre/PyBer_Analysis/blob/6055986b0266942bc32e58754a66b3009de62222/analysis/PyBer_fare_summary.png)

## Summary

Based upon the above data, I have the following recommendations:

* Given the surplus of drivers in urban cities, incentives could be offered to these drivers to provide their services in rural and suburban cities. This would increase the availability of rides in underserviced cities, potentially resulting in more rides.
* Discounts could be offered to riders in suburban and rural cities in order help increase ridership in those cities. With higher average fares each ride has the potential for more earnings, and therefore a higher return on investment, than rides in urban cities.
* Discounts could be offered in different city types during weeks with historically low total fares. For instance, based on the above line chart, discounts could be offered in all city types during the first week of March, and in only suburban and rural cities during the second week of April.

I would highly recommend further research in order to compile data over a longer period of time. Furthermore, I would recommend bringing in weather data to determine what relationships exists between ride data and inclement weather. This would help to better understand the fluctuations in fare data over time.
