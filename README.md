This is a document written to confirm that the MTA_Project repository is working.

#Problem
You are working with a non-profit organization. They are trying to raise awareness about women in technology. They want you to identify the best areas to canvass during the day. They will place street teams at the entrances to various subway stations to collect email addresses. You need to help them optimize the placement of street teams.

#Approach
1. Without assuming too much about the population of New York City, we will narrow
   down the focus to Manhattan, where there is a mixture of students and working
   professionals.
2. Any outliers will be removed. Total count of exits and entries will be taken.
3. I will assume that the best time to canvass are the hours from 11AM to 3PM to
   avoid issues with rush hour. Thus, I will remove all other hours.
   I did not remove duplicate station names because they had unique subway lines
   that ultimately became the final groupby.
4. I will take the second and third weeks of December 2016 to remove any issues with
   Christmas and New Year's.
5. I will add data regarding the female to male ratios by zipcode of the subway stops
   from ![alt tag](City-Data.com).
6. Last, I will make a recommendation based on my findings and offer any suggestions
   for further research.

#Recommendations
1. I would choose to test the first five stops from the following list:
![alt tag](https://github.com/albertnjose/mta_project/raw/master/images/top15.png)





2. Knowing that there are a lot of tourists at Times Square and Grand Central,
   we may want to avoid those areas after the initial test and focus on other areas
   that have a larger population of working professionals and students close by.

3. To avoid a lot of angry commuters on Mondays, I would recommend to canvass on
   Tuesday, Wednesday, Thursday, and Friday. You can see from the graph below those days have peak traffic for those specific stations.
![alt tag](https://github.com/albertnjose/mta_project/raw/master/images/top15_timeseries.png)

4. Last, I would then turn our focus to the stops with the highest female to male ratios.
![alt tag](https://github.com/albertnjose/mta_project/raw/master/images/top_15_femaleratio.png)





#Further research
1. Find which areas have a higher concentration of tech startups.
2. Include analysis of higher income areas where individuals are more likely to make contributions to the cause.
3. It would be good to investigate other subway stops in the Brooklyn or Queens boroughs.
