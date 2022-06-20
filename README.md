# PyBer-analysis
## Project Overview
An analysis of ride share data looking at how trends various metrics relate to the type of city. This 
analysis focused on how the city type differs in total number of rides, total drivers, total fares, and average fare per ride and driver.

## Technologies/Resources
- Data Source: ride_date.csv, city_data.csv
- Software: Python 3.10, Jupyter Notebook
- Libraries: pandas, matplotlib

## Results
### When sorted by city type, the analysis of the ride share data shows that:
- Figure 1: Total number of rides (per city) were highest for Urban cities, followed by Suburban, and finally Rural.
![Number of Rides per City by City Type](https://github.com/manBow1119/PyBer-analysis/blob/main/analysis/Fig1.png)

- Figure 2: Average number of rides by city type demonstrate similar trends with Urban being the highest, then Suburban, and lastly Rural.
![Number of Rides by City Type](https://github.com/manBow1119/PyBer-analysis/blob/main/analysis/Fig2.png)

- Figure 3: Average fares by city type were highest for Rural cities, then Suburban, and last Urban.
![Fares by City Type](https://github.com/manBow1119/PyBer-analysis/blob/main/analysis/Fig3.png)

- Figure 4: Average number of drivers by city type were highest for Urban cities, then Suburban, and last Rural.
![Drivers by City Type](https://github.com/manBow1119/PyBer-analysis/blob/main/analysis/Fig4.png)

- Figure 5: Percent of total fares by city type show that Urban was highest (62.7%), followed by Suburban (30.5%), and lastly Rural (6.8%).
![Percents of Total Fares by City Type](https://github.com/manBow1119/PyBer-analysis/blob/main/analysis/Fig5.png)

- Figure 6: Percent of total rides by city type show that Urban was highest (68.4%), followed by Suburban (26.3%), and lastly Rural (5.3%).
![Percents of Total Rides by City Type](https://github.com/manBow1119/PyBer-analysis/blob/main/analysis/Fig6.png)

- Figure 7: Percent of total drivers by city type show that Urban was the highest (80.9%), followed by Suburban (16.5%), and lastly Rural (2.6%).
![Percents of Total Drivers by City Type](https://github.com/manBow1119/PyBer-analysis/blob/main/analysis/Fig7.png)

- PyBer fare summary shows that weekly totals for fares by city type were always highest for Urban, followed by Suburban, and lastly Rural.
![Total Fares by City Type Over Time](https://github.com/manBow1119/PyBer-analysis/blob/main/analysis/Pyber_fare_summary.png)

## Summary
The data show some noteworthy trends when taken in conjunction. For examples, while total fares are higher in Urban cities (62.7%), it is proportionally lower than might be expected given the percentages of total rides (68.4%) and total drivers (80.9%) in the same cities. This disparity reveals that there may be too many drivers in Urban cities. This is validated when looking at the average number of rides vs drivers; in Urban cities there are considerably more drivers than rides. A reduction in the number of employees is a reduction in costs. The decreased supply of drivers could also increase the fare price for each ride. 
Conversely, the data for average rides vs. drivers in Rural areas show more rides than drivers. With the higher fares in Rural areas, increasing drivers could increase revenue. 
