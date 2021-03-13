# Ford_Go-Trips_Data_Exploration
During this investigation, we will focus on the duration of the trips and the factors that may affect that duration. We may think that the main features are the distance covered for each trip, members' gender, the members' types and the starting day of the trips

## Dataset

The dataset consists of 183,412 bikes trips with 15 features. We have added 
new column for the distance in KM and a new column for the starting day for
each trip. Also a new column for age is added assuming that we are now on 2019.


## Summary of Findings

In the exploration, We found that as the distance of trips increases the duration
of trips increases, but we still have long durations for short distances.
We also discovered that most of the members are men. Also all the members who 
partacipated in all trips are subscribers.

The members' gender and age do not have any effect of duration. Also the trip day does not
have effect on the duration of the trip. But we found that the weekends (Starday and Sunday)
have the lowest number of trips.


## Key Insights for Presentation

For the presentation, I focus on just the influence of the other features of trip duration
and leave out most of the intermediate derivations. I start by introducing the
trip duration variable, followed by the pattern in distance distribution, then plot the
transformed scatterplot.

Then, I emphasized the number of trips in each day and whether the user is male or female.
Finally, Scatter plots are used to show the relation between duration and distance for both 
members gender (male or female) and whether the members partacipated in all trips or no.
