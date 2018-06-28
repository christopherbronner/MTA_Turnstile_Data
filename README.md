# MTA Turnstile Data
Analysis of New York City Subway Ridership Data

[View the jupyter notebook here](https://nbviewer.jupyter.org/github/christopherbronner/MTA_Turnstile_Data/blob/master/MTA_ridership.ipynb)

<img src="mta-1.png">

In this notebook, I analyze ridership data of the New York City Subway to learn about the busiest stations, commute patterns, and ridership distribution over the course of the day and the year. Finally, I develop a simple model that predicts ridership on a given day.

The data set used is provided by the Metropolitan Transportation Authority (MTA) and contains cumulative counter values from the turnstiles in subway stations in four-hour intervals. Using python, I first performed a brief exploration of the data set. Then, I studied the busiest stations and identified stations which are commuter destinations as opposed to commuter origin stations. These data are visualized in maps such as the above one.

Since the data are available for different hours of the day and for every day of the year, I looked into the ridership distribution over the course of the day and the year. For example, I learned that ridership is generally higher during the week, that riders in Williamsburg start their day later than riders in the Bronx, and that ridership goes down on national holidays, when schools are closed, and when it rains.

Additionally, I developed a linear regression model that predicts ridership for a given day based on the day of the week, school schedules, holidays and key weather parameters.

<img src="mta-4.png">
