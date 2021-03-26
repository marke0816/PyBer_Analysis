# PyBer_Analysis

## Overview

The purpose of this analysis is to compare PyBer ride sharing data for different types of cities over the course of the first four months of 2019.  This data can be used to inform business decisions.

## Results

As we can see from the summary data frame below, the more populous the area is, the higher the total fares, the number of drivers, and the number of rides are.  However, the average fare per ride and the average fare per driver are lower for the more populous areas.

![](analysis/summary.png)

This makes sense with supply and demand.  The higher the demand for rides, the more drivers there will be and each ride will cost less.  This results in a lower average fare per driver as the population density increases, rural being the lowest population density and urban being the highest population density.

The total fares by city type are shown in the graph below for the first four months of 2019.

![](analysis/Pyber_Fare_Summary.png)

As one would expect, the three trend lines have disparate values at all times throughout this four month period with the total fares peaking around the third week of February.

## Summary

The disparities among the city types regarding the total fares and average fare per driver are large. If we look at the summary data dataframe, we can see that the number of rides per driver is 1.6, 1.3, and 0.7 for rural, suburban, and urban areas respectively.  Coupled with the average fare per ride data, we can see that the drivers (and PyBer) could be making much more money from the urban areas if there were fewer drivers.  Unfortunately, this suggestion does involve layoffs.

Alternatively, one might consider offering some sort of incentive bonus for the drivers in urban areas to conduct their business in the suburban or rural areas during the slow times for the urban areas.  This would have the effects of possibly gaining extra income from the higher average fares in the suburban and rural areas, desaturating the driver market in the urban areas, and providing more drivers in the lower populated areas to even out the rides per driver numbers.

We would also benefit from collecting additional metrics from each ride.  These metrics would include length (time and distance) of each fare and time from the rider ping to the arrival of the driver.  With these metrics, we would be able to more accurately assess whether or not there are enough drivers in each area.  If riders are waiting a long time for their driver to pick them up, that area might benefit from extra drivers.  Additionally, if we knew the distance traveled and the time it took for each ride, we might be able to more effectively address the disparities in the average fare per driver.  It is entirely possible that many fares in urban areas are very short whereas fares in rural areas tend to be very long.  This additional data would allow us to address whether the disparity in average fare per driver is due to supply and demand or whether it is simply due to the length of the fare.

