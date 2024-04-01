---
# Feel free to add content and custom Front Matter to this file.
layout: frontpage 
#Use layout "home" if you want the posts showing
title: Welcome
permalink: /

---
## Introduction
This is a webpage showcasing a short data-story based on the work done in the DTU 
course: "02806 Social data analysis and visualization-Spring 24"


## The dataset
The dataset which has been worked with is called; "Police Department Incident Reports: Historical 2003 to May 2018" and provides insight into observations of various crimes committed in San Francisco from 2003-2018. While it covers crimes in 2018, we have chosen to only include 
data up to and including 2017, since the 2018 observations are only until May and therefore not for a full year which might disrup the result of some analyses.
It consists of 2.13M observations which are categorized into 14 columns. These include e.g. a crime category (prostitution, car theft, robbery), the day and date of the crime, the time, the district and the coordinates of the crime.

## Analysis
In this section, we'll delve into the analysis of SF Crime Data and explore key insights.
The dataset contains observatinos of 37 different types of crimes. We have however decided to look into vehicle theft. 
The amount of wehicle thefts each day in the period of 2003-2017 can bee seen on the calender plot on Figure 1. 

![This is a calendar plot](https://linchang2.github.io/calendar_vehicle.png)
Figure 1: Calendar plot of number of vehicle thefts in San Francisco in the period 2003-2017.


In the plot there is a clear indication on how the vehicle theft have decreased significantly in the year of 2006. 
While there were often between 40-70 thefts a day in the years of 2003-2005, there are almost no days in the period 2006-2007 where there were more than 40 thefts a day - on average it looks like the number of thefts is around 20.
According to the article "Auto thefts in state decline for first time in decade" (REF) there was in Californaia a statewise 5.5 percentage drop of vehicle thefts between 2005 and 2006. 
Even more impressive is it that "Car thefts were down 22.9 percent in San Francissco". POtential reasons to this decreasing trend are said to be:
1. Car owners buy more preventive devices (e.g. locks for the steering wheels & tracking systems)
2. Police officers increasingly using 'bait cars' to nap thieves
3. License Plate Recognition systems to spot stolen cars
4. Newer cars often have build in alarms



HER ER BOKEH
<iframe src="Bokeh Plot.html" width="800" height="400"></iframe>


One map (use techniques from Week 3 and 4)
One interactive visualization in Bokeh (Week 6)
At a minimum, the Bokeh visualization should contain different data than the exercise we did for Week 6 (it's a plus if it's a new type of viz altogether).
The two other visualization may be repetitions of figures created during the previous lectures, or they may be new.
Make the figures nice. Specifically:
Aim to make the figures visually consistent (color, fonts, etc)
Follow the recommendations from my video on nice figures (Week 2, part 3)
In terms of the amount of text, I envision something like 500-1500 words (including figure captions). Try to write in your own words - the LLMs have a tendency to write a lot of text and not be so precise. So if the writing is all elegantly written but empty prose, we will be critical. It is OK, however, to have the LLM help you get the grammer, etc. right.
It is a plus if you can back up some of your findings with external sources, such as news stories from the area, looking up which building is located at some set of lat,lon coordinates, or similar. (So when you see something happening at some time/place in the data, see if you can understand it more deeply by investigating outside the dataset.) Use real references at the end of the text to organize your links to the outside world.