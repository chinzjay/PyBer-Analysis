# PyBer Analysis

## Overview of the analysis
The purpose of this project is to analyze how the ride-sharing data differs by city type by creating a Summary DataFrame of the ride-sharing data and a multiple-line graph that shows the total weekly fares for each city type using Pandas and MatPlotlib.

## Results:
Using Pandas and MatPlotlib, the data files(https://github.com/chinzjay/PyBer-Analysis/tree/main/Resources) were imported and analyzed. Using groupby( function, the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type was calculated and a DataFrame was created using the analyzed data (https://github.com/chinzjay/PyBer-Analysis/blob/main/PyBer_Challenge.ipynb).

![Summary Dataframe](https://github.com/chinzjay/PyBer-Analysis/blob/main/summary%20dataframe.PNG)
|:--:|
|Fig 1. Summary DataFrame of the ride-sharing data by type|

*Fig 1* shows the Summary Data Frame of the ride sharing data by city type. We can see from the table that 
- The total number of rides in Urban(1625) is the highest compared to the number of rides at SubUrban(625) and Rural(125).
- The number of drivers is the highest at Urban(2405) when compared to Suburban(490) and Rural(78).
- The totalfFares at Urban is the highest compared to the Total Fares at Suburban and Rural.
- The average fare per ride is the highest in Rural($34.62) compared to Suburban($30.97) and Urban($24.53).
- The average fare per driver is the highest at Rural($55.49) as compared to Suburban($39.50) and Urban($16.57)

Using the pivot() function, loc method and resample() function a DataFrame *(Fig 2)* was created to get the data in weekly bins and to show the sum of the fares for each week. 
![final DF](https://github.com/chinzjay/PyBer-Analysis/blob/main/final%20DF.PNG)
|:--:|
|Fig 2. DataFrame created to show the sum of the fares for each week|

A multiple-line graph (https://github.com/chinzjay/PyBer-Analysis/blob/main/analysis/PyBer_fare_summary.png) that shows the total weekly fares for each city type was plotted using the data from the DataFrame in *Fig 2*.

### Analysis
We can conclude from the above results that the number of rides and drivers are several folds higher in Urban than Rural and Suburban. The average fare per ride and driver is higher in Rural and Suburban than Urban. We can see that there is a negative relationship between the number of drivers and the total fares of each city type data: Higher the number of drivers in the city, lesser the average fare per ride and average fare per driver.

## Summary
I would make the following recommendations to the Ms. V. Isualize, CEO for addressing the disparities among the city types.
-
