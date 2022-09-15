# **Pyber Analysis**

## **Overview of Analysis** 
This project analyzed ride-share data from January to early May of 2019 to provide business recommendations on how to improve access to ride-sharing services and determine affordability for underserved neighborhoods. In this project, we utilized Pandas, Jupyter Notebook, and Matplotlib to provide the analysis below.

We used the city_data and ride_data csv files to merge into one dataframe to conduct this analysis. From there, we examined the ride-share data by city type and provided recommendations to the CEO for addressing any disparities among the city types.

***
## **Results**
### **Average Number of Drivers & Fare by City Type**
INSERT PICTURE FIG1

<sub>In this bubble chart, we can see the relationship of the city type with the total number of rides per city and average fare per city. The circle size correlates with the driver count by city. </sub>

### **Rides by City Type**
INSERT PICTURE FIG2 (Box & Whisker)
<sub> Urban cities had the highest average number of rides at 25, Suburban cities at 17, and Rural cities at 7 rides per city. The average number of rides in rural cities is about 3.5x and 2.5x lower than urban and suburban cities, respectively. There is also one outlier value with a city at 39 rides.</sub>

INSERT PICTURE FIG6 (Pie Chart)
<sub> Urban cities had the highest percentage of rides at 68.4%, with Suburban cities following at 26.3%, and Rural cities at 5.3%. </sub>

### **Rides by Driver Counts**
INSERT PICTURE FIG4 (Box & Whisker)
<sub> Average number of drivers in Urban cities is 37, while Suburban cities have 14, with Rural cities having the least at 4. </sub>

INSERT PICTURE FIG7 (Pie Chart)
<sub> Urban cities had the highest percentage of drivers at 80.9%, Suburban cities at 16.5%, and Rural cities at 2.6%. </sub>

### **Fares by City Type**
INSERT PICTURE FIG3 (Box & Whisker)
<sub> Rural cities had the highest average fares at $34.62. Suburban cities trailed next at $30.97. Urban cities had the cheapest average fares at $24.53. No outliers were found in the data. </sub>


INSERT PICTURE FIG5 (Pie Chart)
<sub> Urban cities had the highest percentage of total fares at 62.7%, with Suburban cities following at 30.5%, and Rural cities at 6.8%.</sub>

INSERT PICTURE Challenge: Pyber_Fare_Summary (Line Chart)
<sub> This chart shows weekly fares for each city type. It can be seen that Urban cities have the highest revenue compared to Suburban and Rural cities. The highest peaks of revenue were seen in the month of April for Rural cities, in the month of February for Suburban cities, and in February and March for Urban cities. </sub>

### Ride-Share Summary DataFrame by City Type
INSERT PICTURE Pyber_Summary_DF 
<sub> This table confirms that while Urban cities have the highest density of rides and driver counts, Rural cities have the lowest density of rides and drivers, leading to higher average fare for each ride as well as the average fare for each driver. </sub>


***
## Summary
Based on the results above, we are recommending these three recommendations to address any disparities among the city types.

1. It can be seen that there are more drivers than rides in Urban cities. This could eventually lead to a lack of demand, leaving some drivers without rides. Marketing in Urban cities could help increase the number of riders, ensuring continued rides for the drivers.
2. This data focuses only on January through May 2019, which doesn't give a full view into the trends throughout the year. Having the full year data would help us understand when there is a higher need for drivers so that Pyber can hire more drivers around the busier times.
3. Rural cities have the least number of rides and drivers. A lot can be done here to increase the supply of rides (promotions, marketing, etc) as well as to hire more drivers. Doing so, would help increase the number of rides and drivers, expanding the revenue of Rural cities.


## **Links**
Pyber Challenge Code: 
Pyber Module Code: 
Analysis Folder: 
Resources Folder: 


***
## Resources
Python version 3.9.12 | Jupyter Notebook version 6.4.8 | Matplotlib version 3.5.1