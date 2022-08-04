# PyBer_Analysis
PyBer is a Ride Share service, this is analytics performed on their data
## Project Overview & Objective:
As a data analyst at PyBer, a ride-sharing app company valued at $2.3 billion. I have been assigned a project to analyze all the rideshare data from January to early May of 2019 and create a compelling visualization for the CEO, V. Isualize.
I am charged to create charts and visualizations that will help PyBer determine Access to Ride Sharing Services and determine Affordability for under served neighborhoods. 
This will be accomplished by analysis ride sharing data and chart relationships between neighborhoods served, driver counts & fares charged.
## Lists & Deliverables:
Importing data into a Pandas DataFrame.<br>
Merge DataFrames.<br>
Create a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural.<br>
Determine the mean, median, and mode for the following:<br>
<i>The total number of rides for each city type.<br>
The average fares for each city type.<br>
The total number of drivers for each city type.</i><br>
Create box-and-whisker plots that visualize each of the following to determine if there are any outliers:
<i>The number of rides for each city type.<br>
The fares for each city type.<br>
The number of drivers for each city type.<br></i>
Create a pie chart that visualizes each of the following data for each city type:<br>
<i>The percent of total fares.<br>
The percent of total rides.<br>
The percent of total drivers.</i><br>
## The Challenge:
Using Python and knowledge of Pandas, we need to create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, we need to create a multiple-line graph that shows the total weekly fares for each city type.<br> 
Finally, submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.
## Analysis Visualizations:
### Overview of the Ride Sharing Data
![PyBer Ride Sharing Data](https://github.com/lallben/PyBer_Analysis/blob/main/Analysis/Fig1.png)
### Distribution of Riders by City Type
![Rider Count](https://github.com/lallben/PyBer_Analysis/blob/main/Analysis/ridecount_box&whisker.png)
### Distribution of Fares collected by City Type
![Rider Fare](https://github.com/lallben/PyBer_Analysis/blob/main/Analysis/ridefare_box&whisker.png)
### Distribution of Drivers by City Type
![Driver Count](https://github.com/lallben/PyBer_Analysis/blob/main/Analysis/drivercount_box&whisker.png)
### Percentage of Rides across City Types
![Rider Count Pie](https://github.com/lallben/PyBer_Analysis/blob/main/Analysis/piechart_rides.png)
### Percentage of Fares Collected across City Types
![Rider Fare Pie](https://github.com/lallben/PyBer_Analysis/blob/main/Analysis/piechart_fares.png)
### Percentage of Drivers across City Types
![Driver Count Pie](https://github.com/lallben/PyBer_Analysis/blob/main/Analysis/piechart_drivers.png)
## Observations:
- The Bubble Chart of the whole data shows quite clearly that the largest concentration of Rides and the Driver Counts are in the Urban City Type. However, the Fares charged are higher in the Rural City Type where the # of rides are considerably lower.
- The purpose of the Box & Whisker Charts is show the distribution of the data across the population and they show that:<br> 
<i>The average Fares charged in the Urban Areas are approx $25 per ride whereas those in the Rural areas are between $35-$40 per ride.<br>
The average rides in the Urban City Type are 24 as compared to 6 in the Rural City Type.</i>
- The Pie Chart that show the ditribution of the market share across the City Types, reflect that the Urban City Type is by far the leader in Fares collected, # of Drivers as well as the # of Rides

## Recommendations:
Based on the analysis of the data I would like to make the following recommendations:
- The Fares for the Urban City Type need to be adjusted upwards to bring the average Fares to approx. $30 per ride. Since the # of rides are already high and will continue to be that way, it makes more sense to bump up the Revenue. Even a small increase will have a significant psoitive impact on the Revenue without any affect on the ridership. 
- The Fares for the Rural City Type need to be adjusted downward to bring the average Fares closer to $30 oer ride. This will encourage more ridership in that area which is possibly lower due to the higher fares. The downward adjustment of Fares will not have a signifiacnt impact on the Revenue considering the ridership distributions. In fact this may result in an increase in ridership which will supplement the Revenue.
- 
