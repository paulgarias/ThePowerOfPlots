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

[scatterPlot]: Pyber/images/PyberScatterPlot.png
