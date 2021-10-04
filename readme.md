# (Ford GoBike System Data)
## by (Fatema Buhuligah)


## Dataset

This dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

The dataset contains 174875 trip records in February 2019, with 17 variables:
* bike_id
* user_type: Subscriber or Customer
* member_gender
* member_birth_year
* member_age
* bike_share_for_all_trip: Yes or No
* duration_min: The duration of the trip in minutes
* start_station_name
* end_station_name
* start_Date
* start_Hour
* start_Day
* start_Month: All of the records have February for the start month
* end_Date
* end_Hour
* end_Day
* end_Month

## Summary of Findings

* Most of the members in this dataset are of ages between 25-35 years old, the number of trips gradually decreases as the age increases. 90.53% of the trips were taken by subscriber type, whereas 9.47% were taken by the customer type. The majority of members were Male and there are 9.90% of members who share the bike for all trips.

*  Compared to the subscriber, the customer has a higher trip duration. It seems like the customer will rent the bike and use it instantaneously. Whereas subscribers feel they are not in a rush to use the bike since they already have the annual subscription. Trips taken by members with age above 65 are almost 60 minutes or less, whereas the members with age under 65 took more than an hour. So whenever the age increases the duration in minutes decreases.

* The duration of trips on weekends (Saturday & Sunday) are higher than the trips on the weekdays. Also the average duration of trips for subscriber user type among the week days is the almost the same whereas for customer user type jumped to its highest on the weekends, and the rest of the week day it almost closely similar. Members under 60 years old are having the most trips all day long with variety of trip duration in minutes, unlike the members above 50 are having their most trips likely in the first hours of the day, in the early morning and the trip duration almost less than an hour (60 minutes).

## Key Insights for Presentation

* For the presentation, I focus on trip duration and trip count. I start by finding the relationship between user characteristics & trip count by presenting different type of visualization (Histogram, Pie Chart & Bar Plot). Then I found the relation between trip duration and user characteristics like (member age & user type). 
* Afterwards, I introduce the different time periods like (the weekdays or the hour of the day) and its relation with the trips duration based on different user characteristics.


## References

* https://www.geeksforgeeks.org/selecting-rows-in-pandas-dataframe-based-on-conditions/
* https://datavizpyr.com/how-to-annotate-bars-in-barplot-with-matplotlib-in-python/