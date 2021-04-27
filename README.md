# Overview of PyBer Ride-share Data Analysis

This project is about analyzing the ride-share data from PyBer company using two datasets - *city_data.csv* and *ride_data.csv*. The *city_data.csv* dataset contains information about the name of 120 cities, total drivers and type of city e.g., Urban, Suburban or Rural. And the *ride_data.csv* dataset contains 2,375 entries of ride-sharing information of those cities in 2019 including date, time, fare and ride ids. The key deliverables of this analysis are - 
  
  (1) to create a summary dataframe having total rides, total drivers, average fare per ride and average fare per driver for each type of cities.
  (2) to create a multiple line plot that shows the total weekly fares for each type of city.
  
## Results

After importing the required dependencies, the .csv datasets have been loaded into the *PyBer_Challenge.ipynb* jupyter notebook. For the sake of analysis, *city_data_df* and *ride_data_df* dataframes have been merged on the common column *"city"* to form a comprehensive dataframce *pyber_data_df* as shown below.

![Merged PyBer Dataframe](Resources/pyber_data_df.png)

For both the *ride-count* and *driver-count* in each city type, Urban cities have the highest score as shown in the following bar-chart.

![Ride & Driver BarChart](Resources/ride_driver_barchart.png)

In terms of *average fare* for each city type, Urban cities show lower average fares but a lot more rides than Suburban and Rural cities. Rural cities have higher average fares but lower number of rides. The following scatter-plot / bubble-chart explains the scenario.

![Fare, ride, per city Bubble Chart](analysis/Fig1.png)

If we dive down a little further into the dataframe, we can get the data distribution info like mean, median, range of data, outliers (if any) etc. from the  *Ride Count Data*, *Ride Fare Data* and *Driver Count Data* for each city type, as shown below.

![Ride, fare, driver Box & Whisker Plot](analysis/Fig2.png) ![](analysis/Fig3.png) ![](analysis/Fig4.png)

The similar analysis can better be visualized using pie-charts as shown below.

![Ride, fare, driver Pie Chart](analysis/Fig5.png) !(analysis/Fig6.png) !(analysis/Fig7.png)
