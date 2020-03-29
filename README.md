# PyBer_Analysis
## Project Overview
The CEO would like an overall snapshot for the ride-sharing data. In addition to the scatter and pie charts, we will need to show a summary table of key metrics of the ride sharing data by city type, and a multiple line graph that shows the average fare for each week by city type. To gather data for summary DataFrame we will need to:

 - Find total rides in each city type.
 - Find total drivers in each city type.
 - Find total fares in each city type.
 - Use total rides and total fares to find average fare per ride.
 - Use total drivers and total fares to find average fare per driver.
 - Add the series' to a pandas DataFrame.

To create the multiple line graph we will need to:

 - Create copy of summary DataFrame that only has Date, City Type, and Fare Columns.
 - Set index to datetime datatype.
 - Calculate the sum of the fares by the type of city.
 - Create pivot table DataFrame with Date as index and City Type as columns.
 - Create DataFrame from pivot table between dates 2019-01-01 and 2019-04-28.
 - Resample data into weekly bins.
 - Plot the DataFrame using fig, ax approach
 
 ## Resources
 - Data Source: schools_complete.csv, students_complete.csv
 - Software: Python 3.7.6, Jupyter Notebook 6.0.3
 - Libraries: Pandas, Matplotlib, Numpy
 
 ## Summary
 ### DataFrame
 The summary DataFrame shows as cities progress from rural to urban, the number of total rides, total drivers, and total fares increase, while the average fare per ride and average fare per driver decrease. The ratio of drivers to fares decreases from 1.60 in rural cities to 0.68 in urban cities which is a contributing factor to the overall decrease in fare per driver. There are likely many more factors contributing to these metrics such as population density, traffic patterns, and surge price adjustments, however, further data analysis will be required to draw accurate conclusions. 
 
 ### Multiple Line Graph
 The line graph shows, in terms of over all revenue week to week, urban cities are the best performers, followed by suburban, then rural cities. The third week in February was the highest performing week for urban and suburban cities and the second highest performing week for rural cities. Overall, the charted changes over time are relatively uniform without any outliers. There are likely a number of social and environmental factors affecting that data that are not entirely obvious with this limited dataset and analysis. In order to further understand the data we will need to ask questions of data such as: What was the weather like in the respective cities during this time? Were there holidays/sporting events/festivals taking place during this time? How was public health during this time? Were students off on break during this time? As more questions are answered we can build a more coherent data driven story.
 


