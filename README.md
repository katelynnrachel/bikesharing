# bikesharing

## Overview
The purpose of this analysis was to create visuals using Tableau Pubic based on New York citibike data, to potentially recreate the same bike sharing program in Des Moines. I had initially created visuals to determine the overall number of trips, find the proportion of short term customers to annual subscribers, find the peak riding hours in August, and answer various other questions. For the challenge, I converted the "tripduration" column of our data to a datetime data type in jupyter notebook, and then created visuals that showed the length of time that bikes are checked out for all riders and genders, the number of bike trips for all riders and genders for each hour of each day of the week, and the number of bike trips for each type of user and gender for each day of the week. 

[link to dashboard](https://public.tableau.com/app/profile/katelynn.youssefyeh/viz/bcs14-challenge/TopStartingLocations "link to dashboard")

## Results
![Gender Breakdown](https://user-images.githubusercontent.com/107594280/206331169-43965dc8-142f-456c-be49-e66560d9a459.png)
- From our initial analysis, we can see the breakdown of the count of different genders using the bike program. From this, we can see that the majority of users are males, and therefore are an important target demographic to market to.

&nbsp;
&nbsp;
&nbsp;

![Top Starting Locations](https://user-images.githubusercontent.com/107594280/206331363-54bee3b4-b34a-4bed-80b1-60d1bb292592.png)
- This visualization is also from the initial analysis. Here, I have created a map that shows the popular start locations around New York. The size and color of each dot corresponds to the number of citibikes started at those locations. This information is useful as it will help us gage which locations to have citibike racks and to determine which locations users bike from.

&nbsp;
&nbsp;
&nbsp;

![Checkout Times for Users](https://user-images.githubusercontent.com/107594280/206332158-ebdd4da4-d095-4460-9e66-e472763d019e.png)
- This graph shows us that most users take rides with citibike for less than hour.

&nbsp;
&nbsp;
&nbsp;

![Checkout Times by Gender](https://user-images.githubusercontent.com/107594280/206332319-079c8107-81e7-4dc5-bfbd-576e8f165bd2.png)
- Here, we can see that gender does not have an impact on the duration of trips and that the trend remains relatively the same regardless of gender.

&nbsp;
&nbsp;
&nbsp;

![Trips by Weekday per Hour](https://user-images.githubusercontent.com/107594280/206332485-432615ff-a8ce-45c3-8d13-c5b432673a15.png)
- This heatmap depics which days of the week and which hours are most popular for citibike rides. As we can see, between 8AM-9PM and 5PM to 6PM throughout the work week are the most popular times. 

&nbsp;
&nbsp;
&nbsp;

![Trips by Gender (Weekday per Hour)](https://user-images.githubusercontent.com/107594280/206332730-cd67e887-7388-447c-8ada-0d164a87850b.png)
- When looking at how gender impacts trips by weekday per hour, we can see the the trend of overall rides remains true here. However, as we've previously seen based on the pie chart and line graph, men are still taking many more rides than women.

&nbsp;
&nbsp;
&nbsp;

![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/107594280/206332946-4ec6718f-b4ca-4342-8dd1-66245ba94a75.png)
- This visualization reinforces the idea that subscribers make up most rides and that subscribers are mostly male.

&nbsp;
&nbsp;
&nbsp;

## Summary
The resuts of this analysis helps us to better understand the citibike program in New York so than it could be better replicated in Des Moines. We have learned that men make up a majority of users, and that most rides remain under an hour with 8AM-9AM and 5PM-6AM being the peak ride times. We have also learned that Thursday is the most popular day of the read for rides among both men and women. 
For further analysis, I would create a visualization that shows where there is little to none usage of citibikes, so that we may look at the surrounding demographics and learn why they are not utilizing the program. I would also create a visualization that takes temperature into account, to help us better understand how many users are using the bikes for entertainment rather than necessity even during colder weather. 
