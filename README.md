# bikesharing
## Overview
After going on vacation to New York City and utilizing the Citi Bike network to move around the city, the idea came to us to bring a similar business venture to Des Moines, Iowa. Because Citi Bike makes their ride sharing data public, we ventured to examine their data to better understand and explain to potential investors how we would be able to port this model from the East Coast to the Midwest. 

[Link to Tableau Story](https://public.tableau.com/app/profile/charles.carpenter/viz/Tableau_Challenge_16531737812740/UserTripData)

[Link to Results Folder](https://github.com/aKnownSaltMine/bikesharing/tree/main/Results)

## Results
When examining the data throughout the month of August 2019, a couple of trends became clear.
As far as demographics of the customer base go, most of the customer base consists of regular subscribers, with 81% of the total customer base being subscribers.

![Customer Type](https://github.com/aKnownSaltMine/bikesharing/blob/main/Results/Customer_type.PNG)

And, the entire customer base skews pretty heavily male: 

![Gender of customer base](https://github.com/aKnownSaltMine/bikesharing/blob/main/Results/Gender_of_cust_base.PNG)

Now, many assumptions have been made about how the customer base uses the service, firstly that it would primarily used by tourists as a way to move around the city, while still being able to see it. If this would be the case, you most likely would see an up-tick of rides around tourist destinations and more skewed towards weekends or distributed throughout the week. This is not is what is being seen in the data. First, the distribution of what hour of the day that bikes were checked out show a concentration towards weekday rush hours.

![Riding heat map](https://github.com/aKnownSaltMine/bikesharing/blob/main/Results/Trips_by_weekday_for_each_hour.PNG)

With the pattern remaining when you look at the gender breakdown.

![Riding heat map with gender](https://github.com/aKnownSaltMine/bikesharing/blob/main/Results/Trips_by_gender_weekday.PNG)

Now, it might look like it is female riders are not riding during that time because male subset is so much darker, but that is because the total riders skews so much male, that the distribution of color looks off. When male riders are filtered out, we can see the same concentration prominently appear for female customers as well.

![Female Rider Heat map](https://github.com/aKnownSaltMine/bikesharing/blob/main/Results/Female_ride_heatmap.PNG)

Furthermore, when examining the length of time checked out by riders, most check outs skew to under 20 minutes. Not something that you would expect from a tourist going around the city for a day. 

![Customer Checkout Times](https://github.com/aKnownSaltMine/bikesharing/blob/main/Results/Checkout_time_for_Users.PNG)

With the breakdown of Gender: 
![Checkout Time by Gender](https://github.com/aKnownSaltMine/bikesharing/blob/main/Results/Checkout_Time_By_Gender.PNG)

This is further accentuated by the fact that the similar ride heat map repeats itself when looking at customer vs subscriber with the subscribers generally only riding on the weekdays with an up-tick in customer rides on the weekends.

![user trips by gender by weekday](https://github.com/aKnownSaltMine/bikesharing/blob/main/Results/user_trips_by_gender_by_weekday.PNG)

Finally when looking at the distribution of rides during the different rush hours across the city, the ending locations for rides in the morning rush hour and the starting locations during the evening rush hour are concentrated in Lower Manhattan where most of the cities corporate jobs are concentrated as well.

Starting Locations in evening rush hour:

![Starting locations Evening Rush hour](https://github.com/aKnownSaltMine/bikesharing/blob/main/Results/Start_Location_Evening_RushHour.PNG)

Ending Location in morning rush hour:

![Ending location in Morning Rush Hour](https://github.com/aKnownSaltMine/bikesharing/blob/main/Results/End_Location_Morning_RushHour.PNG)


## Summary
Due to the distribution of when rides are occurring and the fact that many of the total customer base fall under the subscribers rather than one time customers, then it is clear that the majority of the customers using the services are using the service as a way to commute into the office. This is also supplemented by the fact that most of the rides in evening rush hour start and most of the rides in morning rush hour end in Lower Manhattan, which is where most businesses are in the city. 

Further ways to understand the business and the customer base in order to better adapt the business model to Des Moines, IA would be to cross examine if the rides begin and end close to subway stations as a way to understand if the commuters are using the bikes to supplement the public transit system. Or if they is no real correlation then we might be able to assume that they are using the bikes for their total commute. 

Another area of focus would be understanding why the customer base skews so largely male during that time. Better understanding that would better prepare the adapatation to Des Moines demographics. 