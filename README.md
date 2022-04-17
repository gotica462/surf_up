# Surf_up

## Overview

Do an analyisis of the temperature trends before opening the surf shop in the city Oahu, Hawaii. Specifically, the temperature data for the months of June and December, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Results

After doing our session queries using SQLite and transforming our data into a pd frame, (See link for the code: https://github.com/gotica462/surf_up/blob/main/SurfsUp_Challenge.ipynb) We could get the summary statistics for the temperatures of the month of June and December in the city of Oahu, Hawaii.

See results below.

![image](https://github.com/gotica462/surf_up/blob/main/JUNE-DECEMBER%20COMPARISON.png)

Based on the results we can see that:



-  The average temperature in June is abput 4 degrees more than in December, meaning that there is not much difference in temperature in those months.
-   While The maximum temperatures in June (85°) and December (83°) are pretty much the same, the minimum temperatures does differ a little June is 64° while in December is 56°.
-   The Standard Deviation in December is .5 higher than in June, meaning that there are more changes in temperature in December.

## Summary

Based on our analyisis of the tempetatures of December in June the temperature factor is not a deterrent factor to go ahead with the Ice cream shop since the changes on such temperature are very little. 
If we want to do a more complete analysis we could also look at the coldest and the hottest month of the year for that city and do a comparison between those two months.We also can do a querie on other factors, like precipitation, but also if we could get the data for the number of people visiting the island we could do an analysis based on that data and see if tourism is affected in any way by the months of the year.
