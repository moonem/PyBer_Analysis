# Overview of PyBer Ride-share Data Analysis

This project is about analyzing the ride-share data from PyBer company using two datasets - *city_data.csv* and *ride_data.csv*. The *city_data.csv* dataset contains information about the name of 120 cities, total drivers and type of city e.g., Urban, Suburban or Rural. And the *ride_data.csv* dataset contains 2,375 entries of ride-sharing information of those cities in 2019 including date, time, fare and ride ids. The key deliverables of this analysis are - 
  
  (1) to create a summary dataframe having total rides, total drivers, average fare per ride and average fare per driver for each type of cities.
  (2) to create a multiple line plot that shows the total weekly fares for each type of city.
  
## Results

After importing the required dependencies, the .csv datasets have been loaded into the *PyBer_Challenge.ipynb* jupyter notebook. For the sake of analysis, *city_data_df* and *ride_data_df* dataframes have been merged on the common column *"city"* to form a comprehensive dataframce *pyber_data_df* as shown below.

![Merged PyBer Dataframe](Resources/pyber_data_df.png)

