# PyBer_Analysis
## Project Overview
The CEO would like an overall snapshot for the ride-sharing data. In addition to the scatter and pie charts, we will need to show a summary table of key metrics of the ride sharing data by city type, and a multiple line graph that shows the average fare for each week by city type. To gather data for summary DataFrame we will need to:

 - Find total rides in each city type.
 - Find total drivers in each city type.
 - Find total fares in each city type.
 - Use total rides and total faresto find average fare per ride.
 - Use total drivers and total fares to find average fare per driver.
 - Add the series' to a pandas DataFrame

To create the multiple line chart we will need to:

 - Create copy of above summary datafrom that only has Date, City Type, and Fare Columns.
 - Set index to datetime datatype
 - Calculate the sum of the fares by the type of city
 - Create pivot table DataFram with Date as index and City Type as columns
 - Create DataFrame from pivot table between dates 2019-01-01 and 2019-04-28
 - Resample data into weekly bins
 - Plot the DataFrame using fig, ax approach
 
 ## Resources
 - Data Source: schools_complete.csv, students_complete.csv
 - Software: Python 3.7.6, Jupyter Notebook 6.0.3
 - Libraries: Pandas, Matplotlib, Numpy
 
 ## Summary
 The summary DataFrame shows as cities progress from rural to urban, the Average Fare per Ride and Average Fare per Driver progressively get lower in a linear fashion. There are likely a number of factors contributing to these metrics but one that stands out is the ratio of drivers to fares for Average Fare per Driver which goes from an average of 1.60 in rural cities to 0.68 in urban cities. The Average Fare per Ride may be greater in rural areas due to lack of intensification and population density, requiring longer trips.
 


