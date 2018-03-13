# The Power of Plots HW5 (Pyber)

### Paul G. Arias, Ph.D.

### Scatter Plot

We are tasked to try to understand the relationship between the following characteristics of each ride:


* Average Fare ($) Per City - y axis  
* Total Number of Rides Per City - x axis  
* Total Number of Drivers Per City - bubble size  
* City Type (Urban, Suburban, Rural) - bubble color  

The scatter plot below shows the results

!["Scatter Plot"][scatterPlot]

There are a few trends that can be observed from this scatter plot alone.

1) Price as function of rides. We can see that the relationship of price with the number of rides is inversely proportional. That is, when the price is low, there is a corresponding number of high ride volume. 

2) Heterogeneous classification. It can be observed that the classification according to urban, suburban, and rural rides is rather heterogeneous; they do not overlap much. Urban areas have the highest number of rides, and rural areas have the smallest number of rides. 

3) Driver availability matters. In addition to the the relationship between the number of rides and the prices, we can also observe that there is a strong relationship between the number of rides and the number of drivers, depicted by the size of the bubbles, which represents the number of drivers in each city. It suggests that both the number of rides and average prices are functions of the number of available drivers

### Pie Charts

The pie charts are able to provide some idea about the proportion of business metrics attributed to the kinds of cities.

!["Pie Rides"][pieRides]

!["Pie Fares"][pieFares]

!["Pie Drivers"][pieDrivers]

In particular, we can see that the following information.

1) Number of drivers in by city types are distributed statistically over (nearly) orders of magnitude. The number of drivers in urban areas are significantly represented in this data.

2) Together, the suburban and rural areas do provide a good chunk of revenue. Despite the overwhelming amount of business that can be brought in by urban drivers, suburban and rural business is doing well for Pyber's revenue stream.


[scatterPlot]: Pyber/images/PyberScatterPlot.png
[pieRides]: Pyber/images/PyberTotalRidesbyCity.png
[pieFares]: Pyber/images/PyberTotalFaresbyCity.png
[pieDrivers]: Pyber/images/PyberTotalDriversbyCity.png



