# Bikesharing Data Analysis

## Overview

This project involved studying the bikesharing data from the NYC Citi Bike website. We downloaded the data for rides that occured in August 2019 to study and provide insights to the team which wants to start a similar bikesharing service in Des Moines, Iowa. We used Python and the pandas library to transform some data and then imported the data into Tableau to create visualizations to help the team. 

The Tableau dashboard is published and the link is as follows:
[Tableau Dashboard](https://public.tableau.com/profile/dushyant.katragadda#!/vizhome/NYCCitiBikeAnalysisfordatainAug2019/NYCCitiBikeAnalysis)

## Results

Some of the visualizations we reviewed are heat maps showing the popular locations, bike rides by hour of the day, by gender, by user type, by day of the week etc. 

### To review the top starting locations for bike rides in NYC

![Top_Starting_Locations](https://github.com/dkatragadda/bikesharing/blob/main/Resources/Top_Starting_Locations.png)

The screenshot shows that most rides originated in Manhattan in mid-town or lower. 

### To review the bike rides by hour of the day

![Bike_Rides_by_hour](https://github.com/dkatragadda/bikesharing/blob/main/Resources/Bike_rides_by_hour.png)

Majority of the bike rides originated between 5pm and 7pm. 

### To review trips by day of the week and hour of the day

![Bike_Rides_by_day_of_week](https://github.com/dkatragadda/bikesharing/blob/main/Resources/Bike_rides_by_day_by_hour.png)

The screenshot shows that the rides volume during the week (Mon-Fri) is concentrated between 7am and 9am and again between 5pm and 7pm. The rides over the weekend (Sat-Sun) are spread out over the day (9am to 6pm). 

### To review user type by gender

![Usertype_by_Gender](https://github.com/dkatragadda/bikesharing/blob/main/Resources/Riderbase_by_usertype_and_gender.png)

The data shows that most riders of the NYC Citi Bike program are subscribers and a larger proportion of the userbase is Male and 65% of the rides are taken by males. 

### To review bike rides by day of week by gender by hour

![Bike_Rides_by_Gender_by_day_and_hour](https://github.com/dkatragadda/bikesharing/blob/main/Resources/Bike_rides_by_day_by_hour_by_gender.png)

The screenshot indicates that the rider patterns across the male and female genders are similar with respect to the time of day or day of week. The volume of rides by male users is higher as indicated in the previous screenshot. 

### To review bike rides by gender by day of week by usertype

![Bike_Rides_by_Gender_by_day_by_usertype](https://github.com/dkatragadda/bikesharing/blob/main/Resources/Bike_rides_by_gender_by_usertype.png)

The screenshot indicates that male subscribers make up most of the rider volume during the week days but also contribute to the volume on the weekends. 

### To review trip duration

![Bike_Rides_by_trip_duration](https://github.com/dkatragadda/bikesharing/blob/main/Resources/Ride_duration.png)

Most rides end within an hour and maximum number of rides end within 5 minutes of starting the rides which indicates that the rides are short and mostly commuter based. 

### To review trip duration by gender

![Bike_Rides_by_trip_duration_by_gender](https://github.com/dkatragadda/bikesharing/blob/main/Resources/Ride_duration_by_gender.png)

The rider patterns are consistent with trip durations across genders where most trips end within 5 minutes of their ride.

## Summary

The results show that the bikesharing service is a valuable service to be provided to riders in the city. In this case, the team should proceed with setting up the bikeshare service in Des Moines, Iowa based on the insights generated through this analysis. 

Some additional visualizations for future analysis would cover:
1. To design a plot/visualization to understand when bikes need some maintenance/service - this could cover what time of the day, age of the bike or frequency of service necessary
2. To review bike stations capacity at the busy times of the day to ensure that all stations are equipped with bikes and if necessary, re-distribute the inventory across different bike stations to ensure that there are enough bikes during the peak hours at the most popular stations. 
