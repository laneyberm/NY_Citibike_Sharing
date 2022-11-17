# NY_Citibike_Sharing

## Project Overview
###  
Investors want to know if they should invest in a citibike sharing venture in Des Moines, Iowa. The core issue we need to think about is what we absolutely need to know in order to create our bike-sharing program in Des Moines. We will use data analysis of New York City Citibike Data from August 2019 to collect information for the investors prior to opening this new business. 

Questions they have include: how many bike trips were recorded during the month of August(beautiful time of the year to rent a bike), number of short-term customers and annual subscribers to the Citi Bike service, peak hours for bike rentals, highest-traffic locations, top locations for starting a bike journey, rider data regarding gender, average duration of a bike ride, and key costs including initial set up and bike upkeep through maintenance.

## Resources
- Data Source: <a href="https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip">201908-citibike-tripdata.csv</a> from the <a href="https://ride.citibikenyc.com/system-data">Citi Bike System Data page</a>
- Software: Jupyter Notebook 6.4.8, Python 3.7.13, Tableau Public 2022.3.0
- Library: Pandas 1.3.5

## Results

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/checkout_times_users.png" width="900">

- Most Bike usage times up to 45 minutes.
- The majority of the bike rides lasted for 5 minutes.

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/checkout_times_gender.png" width="900">

- There is a higher amount of males that utilize the citi bikes but the distribution of trip duration is similar between males and females. 
- The majority of the men's trip duration lasted for 5 minutes
- The women lasted for 6 minutes.

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/trips_by_weekday_per_hour.png" width="900">

- On weekdays, there are more bike trips during the morning commute times (6am to 10am) and the the evening commute times (4pm to 9pm).
- These times correlate with the transit hours for people either heading to or returning from work.
- On weekends, Citibike is more popular during the day.

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/trips_by_gender.png" width="900">

- Males utilize citibikes more than females.
- Wednesday afternoons is less popular time for biking among all genders.

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/user_trips_by_gender.png" width="900">

- The highest amount of utilization are male subscribers.
- Thursday and Friday are the days of most utilization for male and female subscribers.
- Saturday is the most utilized day for normal customers. 

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/bike_maintenance.png" width="900">

- About one third of the bikes are highly used and should be maintained.

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/august_peak_hours.png" width="900">

- The least busy hours are from 1am to 5am which is the most convenient time for maintenance. 

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/top_starting_location.png" width="900">

- The darker and larger circles are the the most popular locations for starting a bike journey.

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/top_ending_location.png" width="900">

- The darker and larger circles are the the most popular locations for ending a bike journey.
- The top ride ending locations are Manhattan's most touristic and busiest areas.

## Link to the Dashboard
[link to Tableau dashboard] <a href="https://public.tableau.com/app/profile/elaine.bermudez/viz/NYC_Bikesharing_201908_16686538901570/Story1">link to dashboard</a>

## Summary and Recommendations
From the checkout times data, we find that male users are the highest utilizations. Optimizing a marketing strategy to a new bike sharing program should be initally geared towards males. From the user trips by gender and weekeday data, we see that there are higher bike utilization for subscribers for all genders. From the bike maintenance and peak hours data, we see that a majority of the bike utilization is 25% of the bikes. The most ideal time to maintain the high utilized bikes would be from 12am to 5am. 

A few recommendations:
- Find the Des Moises population in comparison to NYC. This will help determine the amount of bike to purchase to the intial set up. 
- Find the major transit locations for starting and ending commuters in Des Moises. 

