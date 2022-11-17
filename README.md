# NY_Citibike_Sharing

## Project Overview
###  
Generally speaking, when we think about all of the data we have available to us from Citi Bike, we can come up with several questions that we would want a Tableau visualization to help answer. We need to think critically about which questions are the most important for our analysis. This is an important skill to master.

The core issue we need to think about is what we absolutely need to know in order to create our bike-sharing program in Des Moines. After thinking through various questions, you settle on the first question you would like the data to answer: how many bike trips were recorded during the month of August? Since August is a beautiful time of the year to rent a bike, we want to use this data as a starting point to determine how many rides we could expect in the city of Des Moines.

We've established that one of our primary goals when using Tableau is to answer questions using data. We want to create a visualization that ultimately answers our question or leads us closer to answering the original question. Our first question is, "how many trips were recorded during the month of August?"

Another piece of data you'll want to look into is the number of short-term customers and annual subscribers to the Citi Bike service. This will help us determine the types of customers we could expect for a bike-sharing company in Des Moines. Specifically, you want to find out how the proportion of short-term customers to annual subscribers has changed.

Since August can be a good month to visit New York City, next we'll figure out the peak hours for bike trips during the month of August. This will help our investors get a ballpark estimate of how many bikes we might need in Des Moines.

You've answered two questions about the data using Tableau: (1) what is the breakdown of annual subscribers vs. short-term customers, and (2) what are the peak hours for bike rentals? These answers will help you broker a strategic conversation with investors. There are more questions to ask the data, however. For example, what are the highest-traffic locations? Understanding both when and where people use Citi Bike will help you plan your pilot in Des Moines. So you decide to find the top locations for starting a bike journey among Citi Bike customers.

Another question we have for the data—beyond the where and when—is the who. What can the data tell us about the riders themselves? Often, the first place we start when understanding a population is gender.

We know the breakdown of riders by gender, but learning other details about the riders will further assist our analysis. Let's take a look at the average duration of a bike ride, by age. This will help us set expectations for trip duration in Des Moines

Kate is trusting you to put together a strong presentation for the investors, so you're trying to think like one. What might the key costs be in a bike-share business? You mull over this question until inspiration strikes: beyond the initial setup, bike maintenance will likely be one of the biggest expenses. So, what can the data tell us about the upkeep bikes might need? A likely concern of investors is the cost of bike upkeep. The bikes used most frequently will probably be the ones that require the most maintenance, so we'll need to determine which bikes have the highest sum of "Number of Rides."

Your investors are curious about the bike utilization during the month of August. You'll need to show the utilization of each Citi Bike in New York City. This will continue to help you understand the needs of a bike-sharing business in Des Moines. Now that we've found the number of trips per bike during the month of August, we should figure out how long those rides are and if there are bikes that need more attention than others. We'll use the bike ID as a metric for this part of the analysis and create a packed bubbles visualization. 

The aim of the project is to convince investors that a bike sharing program is a solid business proposal. An analysis is carried out on on existing bike data from New York city to figure out how the bike sharing works and show the profitability of a bike sharing business.

### In this project, we will 

## Resources
- Data Source: <a href="https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip">201908-citibike-tripdata.csv</a> from the <a href="https://ride.citibikenyc.com/system-data">Citi Bike System Data page</a>
- Software: Jupyter Notebook 6.4.8, Python 3.7.13, Tableau Public 2022.3.0
- Library: Pandas 1.3.5

## Results

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/checkout_times_users.png" width="900">

- Bikes are mostly used up to 45 minutes.
- The majority of the bike rides lasted for 5 minutes.

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/checkout_times_gender.png" width="900">

- The Males use Citi Bike about 2.5 times more than females.
- The majority of the men's trip duration lasted for 5 minutes
- The women lasted for 6 minutes.

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/trips_by_weekday_per_hour.png" width="900">

- On weekdays most of the trips come to morning and evening hours. During the weekdays there is a lot of bike use between the hours of 6 AM to 10 AM and 4 PM to 9 AM. 
- This times correlate with the transit hours for people either heading to or returning from work.
- on weekends Citi Bike is more popular during the day.

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/trips_by_gender.png" width="900">

- males are more active users of Citi Bike than females
- The bikes are predominantly used by the Males between the hours of 6 AM to 10 AM and 4 PM to 9 AM
- Wednesdays afternoon is less popular time for biking among all three genders.

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/user_trips_by_gender.png" width="900">

- Male Subscribers are the dominant users of the bike sharing services.

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/bike_maintenance.png" width="900">

- About one third of the bikes are highly used.
- 

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/august_peak_hours.png" width="900">

- The peak hours for bike trips during the month of August
- If we need to do maintenance on a bike, knowing the peak usage hours will help us plan for the best time to do that
- The least busy hours are from 1am to 5am.

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/top_starting_location.png" width="900">

- The data to find the most popular stations in the city for starting a bike journey
- The top ride starting locations/stations are Manhattans most touristic and busiest areas

<img src="https://github.com/laneyberm/NY_Citibike_Sharing/blob/main/static/images/top_ending_location.png" width="900">

- The data to find the most popular stations in the city for ending a bike journey
- 

## Summary
By replacing 

https://public.tableau.com/app/profile/elaine.bermudez/viz/NYC_Bikesharing_201908_16686538901570/Story1
