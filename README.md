# Bikesharing with NYC CitiBike data

## Analysis Objective
Using Tableau Public and Jupyter Notebook to analyze and create visualization of NYC CitiBike sharing data from August, 2019. 

## Analysis Overview
Link to [Tableau Public Dashboard]([url](https://public.tableau.com/app/profile/ash3758/viz/NYCCitiBikeAnalysis_16536068955300/Story1?publish=yes))

The framework for this project was to analyze bikeshare data from CitiBike in New York City to convince stakeholders that a bike-sharing program in Des Moines is a solid business proposal. The detailed bike trip analysis is to to solidify the proposal to present to stakeholders. 

For this analysis, we used Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

1. Show the length of time that bikes are checked out for all riders and genders
2. Show the number of bike trips for all riders and genders for each hour of each day of the week
3. Show the number of bike trips for each type of user and gender for each day of the week

## Analysis Results
Despite the differences between Des Moines and NYC, the initial results indicate that CitiBike might appeal to the former and stakeholders. 

The following image shows the number of riders that are subscribers and the gender breakdown.

![image](https://user-images.githubusercontent.com/96931376/170596397-d8d1ba06-8802-4a92-b8aa-50c8be282a65.png)

The following map displays the stations that recorded the start of bike trips. The quantity correlates with the size of the circles and shade of the green.

![image](https://user-images.githubusercontent.com/96931376/170597660-e7558055-d22f-4809-83b3-fed7af7254f5.png)

The following chart shows the number of active bike rides that were initiated during the day for the month of August.

![image](https://user-images.githubusercontent.com/96931376/170599626-83db7de7-9f1c-406f-841e-a3c5da427e1d.png)

The following heatmap shows weekly usage patterns which ranges from 360 to 44,905 as indicated from light to dark. 

![image](https://user-images.githubusercontent.com/96931376/170601234-29e633b9-9d47-49f1-a223-82b5ce960083.png)

This heatmap shows the difference in gender usage.

![image](https://user-images.githubusercontent.com/96931376/170601718-d42826df-84ad-46ee-a854-32bf90dab988.png)

The following image shows the checkout times for bike rides for users overall. 

![image](https://user-images.githubusercontent.com/96931376/170601909-f6e39a84-1394-44ac-a1b2-31a2f1057a6a.png)

The following image breaks down the gender differences associated with checkout times for bike rides. 

![image](https://user-images.githubusercontent.com/96931376/170601998-e8e943b1-c2f9-481f-9e1d-18d4d03d3801.png)

The following image shows the average trip duration by the age of the bike rider. 

![image](https://user-images.githubusercontent.com/96931376/170602117-cf68cc10-1411-4025-a993-7ac59a407e57.png)

## Analysis Summary
Overall, bikeshare services appear to be widely popular amongst metropolitan areas. The primary user base for bikeshare services skew towards male subscribers. Based on trip start/end times and duration, the primary usage is related to morning and evening commutes.

Studies of the traffic flow for bikeshare riders and a poll regarding safety concerns may be worth additional research for stakeholders. 





