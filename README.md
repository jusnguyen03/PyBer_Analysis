# PyBer_Analysis

## Project Overview
I just landed a job as a Data Analyst for a company called PyBer, a Python based ride sharing app company. My first assignment is to perform an exploratory analysis on the data from PyBer in regards to their ride sharing. To aid with this process, I will need to create several types of visualizations to tell a compelling story about the data. With resources provided, I will need to show a relationship between the types of cities as it relates to the total number or riders and drivers that use PyBer and the rates the riders pay. This analysis will help PyBer improve access to ride sharing services and determine affordability for underserved neighborhoods.

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.6.1, Jupyter Notebook, Matplotlib

## Challenge Overview
### Part 1
Using the data sources provided, create a new summary DataFrame that showcases the total rides, total drivers, total fares, average fare per ride and average fare per driver for each city type.

### Part 2
Plot the sum of the fares for each city type using a multiple-line graph. 

In this challenge, we were to use the following in pandas to complete the below objectives:
  - Use groupby, resample, pivot, reset index on a Dataframe
  - Create new Dataframes from multiple groupby() series
  - Format columns and rows in a Dataframe
  - Create a multiple-line graph

## Challenge Summary
Please click on the file "Pyber_Challenge.ipynb" in the repository folder to review the completed challange assignment.

### Part 1

![](https://github.com/jusnguyen03/PyBer_Analysis/blob/master/analysis/challengepart1.png)
After calculating all the statistics in regards to Total Rides, Total Drivers, Total Fares, Average Fare per Ride and Average Fare per Driver for each of the types of cities (Rural, Suburban and Urban) in Pandas Notebook using Python, I created a new dataframe with the results for easy visability. 

Per the new dataframe, we see that in rural cities, there were a lot less rides and drivers available. The average fare per ride and per driver were a lot more expensive than in other types of cities. In urban areas, there was an abundance of drivers available, the cost per ride and driver was much cheaper. Since the rides were much cheaper, and the availability was very high, there was a significant greater amount of rides given. We can assume that the population in urban cities is much larger than in rural cities, so more people will need to request for rides to get around. Since there are more drivers, the cost is probably much lower due to competition. In rural areas, where the population is much lower, and it's so far away from everything, the rides and drivers cost much more. 


### Part 2

![](https://github.com/jusnguyen03/PyBer_Analysis/blob/master/analysis/challengepart2.png)
The multiple-line plot chart displays the sum of fares for each type of city for each week from the dates of January 2019 through end of April 2019. Since the data we used is the same as in part 1 of this challenge, this also shows that the total fares were greater in urban cities, than in suburban and rural cities. This snapshot allows us to see visually and very quickly the trend week to week on how much in total fares were spent on rides.
