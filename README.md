# PyBer Analysis

## Project Overview
Management would like to obtain a summary and some data visualizations on the performance of PyBer in different city types (Urban, Suburban, and Rural). The following steps were taken to obtain all relevant information for this project.

1. Create a ride-sharing summary table by city type.
2. Create a chart for Total Fare by City Type over the period of Jan to April of 2019.

### Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python (3.7.13), Visual Studio Code (1.67.2), Pandas (1.3.5), Jupyter Notebook

## Results
### Purpose
The purpose of this project is to observe if there is any differences in PyBer Statistics between different City Types. Upon examination of the results, there is a very clear difference in PyBer statistics based on the city type within which a driver operates.

### Summary of City Types
Below are the results of the analysis of rider count, driver count, and fare amount between the three different city types:

![Summary of City Types](https://github.com/msshahid21/PyBer_Analysis/blob/main/analysis/Pyber_Summary.png)

As can be seen from the table above, the Total Number of Rides in Urban cities is 1.6 and 12 times higher than Suburban and Rural cities respectively. This result also directly relates to the Total Number of Drivers being a lot higher in Urban cities than the other two types. This is because as there are more rides in Urban cities, the number of drivers required to meet the demand for those rides is higher than Suburban and Rural cities. Finally, the Total Fares earned in Urban cities is also, as a result of more rides, higher than the other two types. However, the average fare per ride is cheaper in Urban cities and a driver in an urban city also earns less fares on average.

### Weekly Fare by City Types
![Total Fare by City Type](https://github.com/msshahid21/PyBer_Analysis/blob/main/analysis/Pyber_fare_summary.png)

The graph above shows the Weekly Fare earned by all Pyber Drivers over the course of the first 4 months of 2019, by City Type. Urban cities seem to have maintained a slight increase in total weekly fare over the 4 months, while Suburban and Rural cities seemed to maintain a similar total fare over the 4 months.

## Summary
In conclusion, PyBer riders have a lot more competition in Urban cities but are still experiencing an increase in weekly fares. This implies that there is still room for more drivers to potentially take up rides in Urban cities. However, the potential for these Urban drivers to earn is a lot lower than the other two city types. On the other hand, drivers in suburban and rural cities can earn more per ride than Urban Cities, but the demand for rides is a lot lower therefore resulting in lower total fares earned by these drivers.
