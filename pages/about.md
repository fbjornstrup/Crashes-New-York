---
layout: misc
title: About
---
The dataset used trough out our analysis was found og the following [website](https://www.kaggle.com/new-york-city/nypd-motor-vehicle-collisions). It contains details on different vehicle crashes trough out New York City in the period from 2012-2021, where each row represents a crash. In total, the dataset consistens of 1771638 rows and 29 attributes. Some of the most important iclude: 
- `CRASH DATE`
- `CRASH TIME`
- `BOROUGH`
- `ZIPCODE`
- `LOCATION`
- `NUMBER OF PERSONS INJURED`
- `CONTRIBUTING FACTOR VEHICLE 1`

As the dataset is of such great size, some of our analysis is based solely on 10000 observations, where 1000 observations were selected randomly from each of the 10 years. This is denoted with a (*).



# Errors 

Such a big dataset will of course always contain some erros, which sometimes can be worked around and sometimes you just have to live with it. This is an example of New Yorks finest being not so fine.

The jitterplot(*) shows at what time the different crashes have happened, or at least at what time they are registrered. 

<img src="observations.png" width="550" height="450">

It is clear that there is a tendency towards a lot of the occurences being listed at 13:00, 13:10, 13:20, 13:30 and 14. This may indicate that the exact time of the collision is not always written down, but that it is rounded up or down to 10 minutes, full or half hours. 

Overall this is a human error and tells us that the police are indeed a little bit lazy in noting down the exact time.
