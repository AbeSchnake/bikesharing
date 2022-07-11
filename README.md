# Citi Bike Bikesharing Analysis
## Tableau Dashboard
[link to dashboard](https://public.tableau.com/app/profile/abraham.schnake "Tableau Page")
## Overview
This project is an analysis of the Citi Bike company's data from their New York City locations for the pruposes of a proposed bikesharing venture to be based in Des Moines, Iowa. 

## Results
![Trip Duration](https://github.com/AbeSchnake/bikesharing/blob/main/Images/Trip_Duration.png)
Above is a graph of trip duration in minutes by number of bikes, filtered down to only those trips that toook less than one hour total (Which is the vast majority of the trips that were taken). There is a large spike arount the 5-7 minute duration, and it drops off quickly after that. Very few Citi Bike trips lasted longer than 30 minutes. This suggests that each bike will be able to accomodate many unique customers each day.
![Trip Duration by Gender](https://github.com/AbeSchnake/bikesharing/blob/main/Images/Trip_Duration_by_Gender.png)
Above is a breakdown of trip duration by gender (Male customers are in orange, Female customers are in blue, and customers of unspecified gender are in red.). There are many more male users of Citi Bike than there are female users, suggesting that appealing to that demographic might be an area for improvement if a similar venture is conducted in Des Moines. There is virtually no difference in the amount of time each gender spends per trip.
![Trip Heatmap](https://github.com/AbeSchnake/bikesharing/blob/main/Images/Trip_Heatmap.png)
Above is a heatmap showing the popular times for Citi Bike to be used. As might be expected, the busiest times are the weekday mornings and evenings, corresponding to when many people are travelling to and from work. This is an encouraging sign, as it suggests that using bikesharing for commutes is something that customers are willing to do.
![Trip Heatmap by Gender](https://github.com/AbeSchnake/bikesharing/blob/main/Images/Trip_Heatmap_by_Gender.png)
Above is a heatmap showing the popular times for Citi Bike to be used separated by gender. Once again the data show that men use Citi Bike a lot more than women overall, although there doesn't seem to be much of a difference in the patterns of use between genders. 
![Usertype by Gender](https://github.com/AbeSchnake/bikesharing/blob/main/Images/Usertype_by_Gender.png)
Above is a breakdown of User Type by gender ad day of the week. It can be seen that most users are subscribers rather than one-time customers. As well, it seems that subscribers use Citi Bike more often during weekdays, whereas one-time customers are more evenly spaced throughout the week. This suggests that those users who plan to use Citi Bike as a means of commuting to and from work are more likely to subscribe, which makes sense. Once again there does not seem to be a difference in pattern between male use and female use beyond the fact that there are more male users.
![Starting Points](https://github.com/AbeSchnake/bikesharing/blob/main/Images/Starting_Locations.png)
Above is a map showing the more popular locations for users to begin their trips. It shows that the starting locations that are centrally located are the most popular, and central locations in Des Moines ought therefore to be the most well-stocked.
![Ending Points](https://github.com/AbeSchnake/bikesharing/blob/main/Images/Ending_Locations.png)
Above is a map showing the most popular end points for users journeys. You can see that it corresponds very closely to the map for starting locations, which makes sense, since many people will be making round trips over the course of a full day.

## Summary
In summary, bikesharing seems to be a popular way for citizens to commute in New York City. There is room for improvement among potential female customers, and for the Des Moines company some research should be done on how to accomplish this. For future analysis, it might be useful to see a breakdown of popular starting points by gender and a map of popular ending points by gender. None of the analysis done so far in this project shows a behavior difference between male and female users. and some insight into other metrics broken down by gender might shed some light as to why there are so many more male users than female users.
