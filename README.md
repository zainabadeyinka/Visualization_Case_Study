# FordGoBike System Data Exploration
## by Zainab Akanji


## Dataset

This dataset includes information about individual rides made in a bike sharing system covering the greater San Francisco Bay area for the month of February. The dataset can be found with this link; https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv
There are 183412 bike observations in the dataset with 16 features. Some variables are numeric in nature, but the user_type and member_gender variables are qualitative in nature. There are 174952 observations with 16 features after removing missing rows.


## Summary of Findings

* In this investigation, I aimed to look at the behaviour of the two FordGoBike user types and different gender types in San Francisco Bay Area. Summary of key insights: I wrangled the data preliminarily and removed outliers; I explored the individual variables of interest and I found out that;

* Most trips were between 0 1nd 15 minutes with a peak at 10 minutes

* 75% of bike users are males, about 20% are females and about 5% are of the other gender.

* Most bike users are between the ages of 25-40years with a peak age at 30years.

* The highest number of trips are taken by 8a.m and 5p.m which corresponds to the beginning and end of work hours respectively.

Then I moved on to perform Bivariate Explortation and analysis showed that;

* Users between the ages 25-35years take the most trips that are less than 20 minutes

* Subscribers take most of their trips during the weekday and Customers take most of their trips during weekends

Then on Multivariate Exploration;

* Female customers take the longest of trips

* Male and Female Subscribers are most active by the beginning and end of work hours(i.e 8a.m and 5p.m) while male and female customers take their most trips between 7a.m and 10p.m since customers tend to ride mostly on weekends.


## Key Insights for Presentation


For the presentation, I aimed to look at the behaviour of the two FordGoBike user types and different gender types in San Francisco Bay Area. I start by introducing the distributon of trips in minutes, counts of the two user types and relative frequency of different member gender. Then I showed a boxplot of the trip distribution of user types and gender. I also showed a countplot of the distribution of bike trips of user types of different gender at different hours of the day.
 The above visualization plots help to show the findings below;
* Female customers take the longest of trips
* Male and Female Subscribers are most active by the beginning and end of work hours(i.e 8a.m and 5p.m) while male and female customers take their most trips between 7a.m and 10p.m since customers tend to ride mostly on weekends.


