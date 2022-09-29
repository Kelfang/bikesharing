# Bike Sharing in Des Moines

## Project Overview

The motivation behind this project is to convince investors that a bike-sharing program in Des Moines makes good business sense. By using Tableau, I can accurately evaluate data from Citi Bike that operates a bike sharing program in New York City. The data used within this project is from August 2019. 

## Resources
* Tableau
* Python
* Pandas library
* Jupyter Notebook 
* Data Sources: .csv files, Citi Bike NYC website, United States Census Bureau website

## Summary of Results
While the overall differences between New York City and Des Moines are notable, I was able to unearth a significant amount of insight into the bike-sharing program that Citi Bike runs in NYC. Below you will find the images from Tableau and a brief description of the story that the data tells us. ***The complete Tableau Story can be found [here](https://public.tableau.com/views/NYCtoDSM/NYCtoDSM?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link).***

-------------

<sub>Introduction to Citi Bike Statistics</sub>
![intro_to_stats](https://github.com/Kelfang/bikesharing/blob/main/images/intro_to_stats.png)

As you can see there are a lot of trips taken in August of 2019! The rentals of Customer vs. Subscriber numbers indicate that many people are using the bikes several times a day and/or month. It’s highly likely that the Customers are tourists visiting the city or residents needing the transportation in a pinch. Traffic congestion is a notorious predicament in NYC and bike sharing can provide a reliable (and cost efficient) way to get around the city. 

-------------

<sub>Trip Duration All Riders</sub>
![trip_duration_all_riders](https://github.com/Kelfang/bikesharing/blob/main/images/trip_duration_all_riders.png)

In the image above, you can see that most bike rides last less than 20 minutes. As we know, Citi Bike has limits on how long bikes can be used – 30 minutes for Customers and 45 minutes for Subscribers – but the line graph above shows that the most common ride duration is five minutes, followed closely by six. Knowing that there is a high number of subscribers within this data, I believe that riders are using the bikes as a mode of transportation instead of riding bikes for enjoyment or exercise.  New York City is also densely populated so riding a bike can also be much faster than going by car, walking or subway depending on the starting and ending point. 

-------------

<sub>Trip Duration by Gender</sub>
![trip_duration_by_gender](https://github.com/Kelfang/bikesharing/blob/main/images/trip_duration_by_gender.png)

Further reviewing the trip duration, we can see that gender doesn’t change the data with any significance. Female riders peak out at six minutes with Male riders topping out at five. The “Unknown” gender group doesn’t have a notable peak and is more evenly spread among six minutes and 26 minutes. It appears that there a few different ways to rent the bikes – through an app or on the street at a kiosk. It’s quite possible that the kiosk doesn’t attempt to collect gender or it’s optional to provide. Some individuals may be more inclined to not provide information since it’s a one-time ride or a few rides over a short period of time.

-------------

<sub>Number of Bike Rides by Hour and Day of Week</sub>
![bike_rides_hour_day](https://github.com/Kelfang/bikesharing/blob/main/images/bike_rides_hour_day.png)

The visual above showcases that the busiest times of bike use on weekdays is 7 AM to 9 AM and then again around 4 PM to 8 PM. This time frame coincides with the start and end of a traditional workday so that could signal the bikes are used to get to and from work. Thursdays had the highest concentration of bike use during the 6 PM hour, with the 5 PM hour on the same day close behind. It is worth noting that there are five Thursdays during August 2019 and five Fridays as well, so that can skew the data slightly with an extra day for the month.  

On weekends bikes were rented more on Saturdays than Sundays but the pattern of activity was very similar. Saturdays start to pick up at 9 AM and wind down around 8 PM. Sunday has a slightly later start (with fewer bikes being used) at 10 AM and slows up by 7 PM. Sunset during the month of August in 2019 ranged from 8:10 PM at the beginning of the month to 7:29 PM at the end of the month. This could also explain why the bike usage started to drop off as the chart shows. Bike riding in a dark city with congestion can pose far more risks than riding during daylight hours. 

-------------

<sub>Number of Bike Rides by Gender (Hour and Day of Week)</sub>
![gender_bike_rides_hour_day](https://github.com/Kelfang/bikesharing/blob/main/images/gender_bike_rides_hour_day.png)

The image above looks at how gender impacts usage (if at all). As you can see, it mirrors what we saw in the previous visual. The highest concentration of bike usage among all genders is still Thursdays during the 6 PM hour. Females biked with some consistency during the 8 AM hour Monday through Friday. In the evenings, the most usage was in the 6 PM and 5 PM hour, also Monday through Friday. On weekends the highest usage was Saturdays’ 12 PM hour.  In the visual with the Unknown gender, the weekends were the heaviest of usage with weekdays being nominal. 

-------------

<sub>Bike Activity by User Type and Gender</sub>
![usertype_gender_bike_rides_day](https://github.com/Kelfang/bikesharing/blob/main/images/usertype_gender_bike_rides_day.png)

Bringing in the User Type further reinforces what we have seen within the last two slides. The heaviest usage is on Thursdays followed by Fridays. Again, this could be the result of having five Thursdays and Fridays in the month of August 2019. Either way, the heaviest usage is still Monday through Friday for Subscribers. Customers, on the other hand, see the most bike rides on Saturdays, with Sundays as the runner up. 

-------------

<sub>Number of Rides and Bikes in Use</sub>
![bikes_in_use_number_rides](https://github.com/Kelfang/bikesharing/blob/main/images/bikes_in_use_number_rides.png)

Shifting focus away from the riders, here I have turned the attention to the bikes themselves. 
This data helps showcase what is needed to keep the ridership at the numbers we’ve seen. In this visual, the number of bikes in use by hour is consistent from 8 AM through 7 PM with some slight variability. On the other hand, during those same hours, we see more volatility in the number of rides by hour. This tells me that while bikes are being used each hour, each bike may not see a high number of riders during that hour. These graphs are a good way to assess the bike inventory. If there weren’t enough bikes to meet the demand, I believe that you would see the Number of Rides by Hour hitting over 200k during those peak usage hours. 

-------------

<sub>Population Comparison</sub>
![population_nyc_dsm_2020](https://github.com/Kelfang/bikesharing/blob/main/images/population_nyc_dsm_2020.png)

In this final slide, I am calling attention to the populations of New York City and Des Moines (along with the immediate metropolitan area). It can be daunting to look at the numbers in New York and try to apply the data to Des Moines. However, per the United States Census Bureau (census.gov), the 2020 population for the Des Moines Metropolitan area was 707,915 which is 8.04% of the New York City population. This translates to far fewer bikes and different behaviors around the use of them. 
As one might assume, Des Moines is more spread out and doesn’t have the dense population that New York City has. Many people drive to and from work without heavy congestion or expense of parking etc. It’s probable that bike usage would lean more towards leisure than replacing a car or public transportation. This is where the focus transitions to Des Moines as a city and how a bike program could successfully participate in everyday life. 

-------------

## Final Thoughts
A bike sharing program in Des Moines can certainly be successful, if executed properly. As the data shows it can be a means of transportation without incurring the expense of vehicle ownership or a way of exploring a city without the cost or maintenance of owning a bike. It would be imperative to understand how Des Moines would use the bikes. At first glance, it’s more likely they would be a tool for leisure or exercise instead of a means of getting to and from work. 

My recommendation is to further dive into the following data to see what additional insight can be gained.

1.	It would be helpful to further dissect the trip durations on weekends vs. weekdays, as a start. Knowing for certain when the longer rides take place would help to understand what a leisure ride might look like. Knowing that Citi Bike caps the ride to either 30 minutes or 45 (depending on the User Type) that might not be adequate for Des Moines if this is to be a more leisure-oriented endeavor. 

2.	Evaluate the data to determine if people are biking solo or with others. This delineation could identify the purpose of the bike ride – is it leisure with family/friends or is it a means of getting to and from destinations. We could accomplish this by isolating the following:  starting location, start date/time, ending location, ending date/time. By further parsing out this data, the group biking trips might be more valuable to a place like Des Moines that doesn’t experience the density of people and places that New York City does. Knowing more about leisure behaviors could put Des Moines on a more successful bike-sharing path. 

