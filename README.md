# NYC Citibike Analysis August 2018

## Project Overview
The purpose of this analysis is to create a series of visualizations depicting New York City Citibike trip data during August 2018. The visualizations intend to convey information regarding trip frequency, trip duration, user demographics, and popular locations. The visualizations for this project were generated using Tableau Public and can be accessed at the following link:

[link to storyboard](https://public.tableau.com/views/NYCCitibikeAnalysis_16484064213070/NYCCitibikeTripsAugust2018?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## Resources
- Data Source: citibike-tripdata.csv
- Software: Python 3.8.9, Tableau Public

## Results

The results of this analysis provide general information on Citibike statistics in August 2018 as well as gender breakdown data and usertype data. See the following figures.

### Ride Duration Frequency

<img width="1017" alt="TripDuration" src="https://user-images.githubusercontent.com/95327115/160299953-3a97e27f-8797-4449-b5a8-b079ae7c376f.png">

The figure above shows a distribution of the length of Citibike trips. A vast majority of the trips are under 1 hour, leading us to believe that it takes under an hour to reach most destinations around the city. There were roughly 146,000 trips that were 5 minutes in duration for the month of August, which is the peak trip frequency. The minimum trip duration is 1 minute and the maximum trip duration for the month is 23 hours and 54 minutes.

### Ride Frequency by Weekday per Hour

<img width="1006" alt="WeekdayFrequency" src="https://user-images.githubusercontent.com/95327115/160299974-2a640ed3-9c49-4900-ad0b-76b595101ade.png">

The heatmap above shows the frequency of Citibike trips for each weekday and hour of the day. During the weekdays, the most trips appear to occur between 7AM-10AM and 4PM-8PM. This correlates with typical travel times for commuters. On the weekends, the most trips appear to occur evenly from 9AM-8PM with slightly greater frequency around lunch time. There is more volume of bikers on Saturday than Sunday and the least traveled day appears to be Wednesday. Throughout the week, there are few trips between the hours of 10PM and 6AM.

### Top Starting Locations

<img width="1005" alt="TopLocations" src="https://user-images.githubusercontent.com/95327115/160299978-9eca2b9f-49dd-4043-81c6-35a602d278de.png">

The map above shows the most popular starting locations for Citibike trips. The greatest volume of trips is in downtown and midtown Manhattan. This is as expected as the areas have a high population density and there are a lot of office buildings and tourist attractions. There are some neighborhoods in Brooklyn and Upper Manhattan that are also frequently used.

### Gender Breakdown

<img width="790" alt="Gender" src="https://user-images.githubusercontent.com/95327115/160299994-202bbd11-3136-4d2f-aec5-ca4dbde053ca.png">

The pie chart above represents the gender distribution for all Citibike trips in August 2018. Of the trips, 65.3% are male, 25.1% are female, and 9.6% are unknown.

### Ride Duration Frequency by Gender

<img width="974" alt="TripDurationGender" src="https://user-images.githubusercontent.com/95327115/160300001-eb886242-0032-4b64-8e72-bf79078e4780.png">

The chart above shows the same information as the first figure with the gender breakdown to illustrate the differences. As expected, the greatest frequency of trips are male as shown in the previous pie chart. The trip duration for males peaks at 5 minutes, 6 minutes for females, and 11 minutes for unknown gender. The trip duration for females is distributed more evenly between 2 minutes and 20 minutes and for unknown gender the trip duration is evenly distributed from 5 minutes to 30 minutes. For all genders, the vast majority of trips are under an hour.

### Ride Frequency by Gender (Weekday per Hour)

<img width="1006" alt="WeekdayFrequencyGender" src="https://user-images.githubusercontent.com/95327115/160300012-7c8432cd-8f36-4d53-bf56-0c5560b2cd2b.png">

The heat map above shows the same information as the second figure with the gender breakdown to illustrate any differences. The trip frequency based on weekday and time of day appear to be similar for males and females. The frequency is likely similar for unknown gender, however there seems to be slightly more frequency of trips on the weekend.

### Ride Frequency by Usertype and Gender per Weekday

<img width="936" alt="WeekdayFrequencyUsertype" src="https://user-images.githubusercontent.com/95327115/160300021-eb996a41-b7f6-43f9-8d9e-8a76d53e1144.png">

The heatmap above represents the volume of trips by weekday, broken into usertype and gender. There appears to be more subscribers than regular customers for males and females. There are also few subscribers with unknown gender. For subscribers, the greatest number of trips are on the weekdays - Monday, Tuesday, Thursday and Friday. Regular customers appear to use the Citibike more frequently on the weekends.

## Summary

Each of the visualizations add to the overall picture of the Citibike customer base, frequented locations, and most popular times for trips. In summary, more than half of the trips are male riders and occur during commuter hours on the weekdays or when the sun is up on the weekends. Most trips are less than an hour in duration and occur in Lower and Mid Manhattan. Also, there are more subscribers than regular customers. For future analysis, two additional visualizations for the Citibike data could be trip duration per bike to understand how many bikes require maintenance or need to be replaced and trip frequency versus weather conditions to determine the effect of weather on bike trips.
