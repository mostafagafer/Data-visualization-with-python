# Effects of Age, Gender and Day of the week on Duration and Distance and how to convert customers into subscribers in Fordbike sharing	

## Dataset

There are 174952 bike-sharing activities in the dataset with 16 features (clients birth date, client gender, duration, locations of 
the ride (start and end station coordinates and start and end station ID), day of the weak of the ride, as well as additional measurements
such as bike ID, user type(being a subscriber of or a customer). Most variables are numeric in nature, but the variables end and start 
station, member type, and member gender are categorical.
data wrangling was carried out on:

1- age column where I groupped the ages in generation. 	  
2- I created a distince column using the the start and end location.


## Summary of Findings

In the exploration, I found that:
1- male used to share bikes more than female
2- people tend to share bikes more often in weekday
3- Longer bike duration is associated with subscribers.
4- Longer distance is associated with subscribers.
5- the majority of the members are between 20 and 40 years old


## Key Insights for Presentation

For the presentation, I focus on just the influence of Age, Gender, and Day of the week on Duration and Distance will have the strongest effect. I used pie plots to investigate the gender and member type, I used line plots to investigate the duration and distance in respect to member age. and in multivariate plots, I combined all of these elements to obtain a full view on the behavior of the member through the weekdays