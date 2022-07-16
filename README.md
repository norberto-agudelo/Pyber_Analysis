# Pyber_Analysis
Module 5 UCF
## Overview 
A new employee has been hired for the PyBer company as Data Analyst to perform an exploratory analysis related with the ride-sharing service data on several cities. The data Analyst must organize and analyze data from two large CSV files.

The first includes data from cities, type of city and number of drivers serving that city. The second one includes all the rides, date and fare of each one. The analyst has to process these files using his/her Python skills and knowledge of Pandas, to eventually  create a summary DataFrame of the ride-sharing data by city type.

Furthermore, he/she must create “multiple-line graph that shows the total weekly fares for each city type” and show a written report with analysis results and recommendations to improve access to ride-sharing for underserved areas. 

So, the main purpose of this project analyze data from cities, rides and drivers based on type of city by using tools stated above to advice the CEO on making decisions process that improve access to ride-sharing service as well affordability for areas that are not good served;
## Results
The first important observation is the great difference of number of cities by type (Urban, Suburban and Rural). There are 120 classified as shown in chart below

![image](https://user-images.githubusercontent.com/107591542/179334660-cd086a44-4103-43e4-90d9-2c809c92a5f9.png)

   ![image](https://user-images.githubusercontent.com/107591542/179334623-9fb5bc5c-e2eb-46c2-8301-70922657330b.png)



Urban cities are 55% of total cities and they are almost two times the Suburban cities and 3.5 times the rural cities. So, it is totally probably that number of rides and drivers should be bigger as well number of rides and fares. 

Effectively, all values in the analysis summary shows an important difference between the city types:

 ![image](https://user-images.githubusercontent.com/107591542/179334669-77674eba-6205-4606-9aac-32eb3536f778.png)


Urban rides are 68% of total rides (2,375). However urban rides are 13 times the rural rides which show that there isn’t a direct correlation between number of cities and number of rides. Population is a variable that must take in account when rides and fares be analyzed based on type of cities.

Urban rides are 2.6 times the Suburban rides close to the correlation between them based on number of cities. It could mean that population density in these types of cities is similar as well as the demand of the service.

Urban drivers are 80% of total (2,973) and they are five times the suburban drivers and 30 times the rural drivers which show again that there isn’t a direct correlation between number of cities and number of drivers.
However, something important to highlight is correlation between number of drivers and number of rides. While rural drivers take an average of 1.6 rides by driver, suburban drivers take 1.3 rides by driver and urban drivers don’t take a least one ride per driver (0.7)

It could mean that service offer is bigger than service demand in urban areas so rural service looks more efficient. Average fare per ride and fare per driver could confirm this observation.

 Rural average fare per ride (34.62) and average fare per driver (55.49) are higher than these in Urban (24.53 and  16.57) and Suburban (30.97 and 39.5). It concludes that ride-sharing service in rural cities are more profitable.

In the other hand is important to analyze sum of the fares for each week to understand what its trend is. To do this a chart is shown below

 ![image](https://user-images.githubusercontent.com/107591542/179334674-626b5401-fe6d-4831-9a00-58d8afe4f126.png)


It seems that rural cities have a similar trend from January to April so because there isn’t any difference on demand during this period and fare is similar, too.  Furthermore,  suburban cities have a similar trend than the rural ones.

Urban cities have less service demand on January but it increases to reach a peak at the end of February and the middle of march. It would interesting to know what happen at the end of February when all types of cities reach a peak.


## Summary
o	It is important analyze what happens with service offering at urban cities because it seems that there are more drivers than the demand requires. It leads to lower profits and less efficiency
o	It is important to encourage people in urban cities to use ride-sharing service because there is enough offering and fair fares based on rural and suburban areas fares. May be out reach programs must be held to increase demand
o	It seems that there aren’t underserved neighborhoods because averages between drivers and rides are low so it shows again that demand is less than service supply, so making decisions must be led to increase the service demand
