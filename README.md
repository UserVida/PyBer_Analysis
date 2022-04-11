## Overview of PyBer Analysis

### Purpose

The purpose of this project was to perform data visualization on a data summary analysis of ride-sharing data by city type. The goal of the project was to create a multiple line graph that displayed the total weekly fares from January to April 2019 by three city types: rural, suburban and urban. The line graph in the analysis was created using the matplotlib library functions. 

The data used in this analysis originated from two csv files that were merged together in the juptyer notebook environment using python code and the pandas library. 

### Resources
* Data Source: city_data.csv, ride_data.csv
* Software: Jupyter Notebook 6.4.5, Python 3.7.11
* Python Libraries: Pandas library, Matplotlib library 

<br>

##  Results

![FaresbyCityType Summary DataFrame](https://user-images.githubusercontent.com/97644424/162650658-c7180590-4232-488f-b671-71a0302caeda.png)

### Total Rides, Total Drivers and Total Fares by City Type

* Urban cities have 3x more rides than suburban cities, and 13x more rides than rural cities.
* Suburban cities have 5x more rides than rural cities. 
<br>

* Urban cities have 5x more drivers than suburban cities, and 31x more drivers than rural cities.
* Suburban cities have 6.3x more drivers than rural cities. 
<br>

* Urban cities make 2x more in fares than suburban cities, and 9x more in fares than rural cities.
* Suburban cities make 4x more in fares than rural cities.
 
 ![Fig1](https://user-images.githubusercontent.com/97644424/162652120-45936af1-3403-4161-984d-67e1984a17c8.png)
<br>
 
### Average Fare per Ride

* The average fare per ride for urban cities is $6.44 **less** than in suburban cities and $10.09 **less** than in rural cities.
* The average fare per ride for suburban cities is $3.67 **less** than in rural cities.

### Average Fare per Driver

* The average fare per driver for urban cities is $22.93 **less** than in suburban cities and $38.92 **less** than in rural cities.
* The average fare per driver for suburban cities is $15.99 **less** than in rural cities. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/97644424/162650739-f59cf8c3-ba88-4075-bbe9-2e996b3bc07b.png)

<br>

## Summary of Recommendations

In order to get a better understanding of our data and address discrepancies in the fare prices between city types, it is important to collect information on the distance travelled for each ride in each city type. Currently, the fare prices, total rides and total drivers amount show a large discrepancy between urban and rural cities. Reducing fare prices and increasing the amount of available drivers may encourage more ride-sharing in suburban and rural cities. However, in order to determine if fare prices can be lowered, more information on the average amount of distance travelled between city types needs to be determined. 

Another way to encourage more ride-sharing in rural and suburban cities is to offer reduced rates during peak demand for ride-sharing services. In the chart above, rides for all city types increased during the last week of February. Determining when there are periods of increased demand will allow the company to capitilize on PyBer ride-sharing promotions. By offering reduced fare rates during these periods of increased demand for taxi and ride sharing services in suburban and rural cities, the hope is the number of rides will increase significantly. If the amount of rides does increase significantly during these periods, it's worth looking into keeping these special offers yearly. 

Currently, the total amount of drivers in the urban cities exceeds the total amount of rides in urban cities by 37:25. To balance this ratio, either the amount of drivers has to be reduced or the amount of total rides needs to increase. Strategies to increase total rides could include expanding advertising, offering incentives such as time-sensitive deals and discounts for frequent customers among other forms of promotion.
