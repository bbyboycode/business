# Analyzing NYC Traffic Data Pre-Pandmeic vs Post-Pandemic
Stanley Guo

## Abstract
The goal of this project was to analyze four years of NYC traffic data, two years prior to the pandemic (2018 - 2019) and two year after the pandemic started (2020 - 2021), to see how the pandemic changed the NYC traffic landscape, in addition to assisting the New York City Department of Transportation (NYCDOT) with their traffic initiave, Vision Zero, which aims to bring down the total number of traffic related deaths down to 0 by 2024.

## Design
The project was designed with the goal of gathering a top-level view of where exactly around the city are traffic accidents occuring, and whether or not these accidents involved any fatalities or injuries.

## Data

The dataset that was used was publicly available on the New York City government website. The original dataset contained a little over 1 million rows. Each row represented a reported accident by the New York Police Department. Important features of the dataset included the date, longitude, latitude, and number of death or injuries, if any, that resulted from the accident.

## Algorithms

Since the majority of the project was to be done using Excel and Tableau, I knew that those softwares wouldn't be able to handle all 1 million rows without extreme lag time or crashing. I used a total of 3,000 rows of data, which was a bit over the recommended 1,000 rows, however, I wanted not only enough data where I would be able to get a large enough sample, but also small enough where Excel and Tableau wouldn't crash when I loaded the data in.

I used Python and the Pandas package to sample the data. I ran a simple script where I randomly retrieved 750 rows of data from each year which added up to a total 0f 3,000 rows.

I used Excel to do all of the cleaning and initial EDA. I cleared up some rows that didn't contain sufficient data, it seems that the NYPD can be lazy at times. I then hid some columns and my resulting spreadsheet contained only the data that I was interested in which was date, location (longitidue, latitude, and borough), and number of deaths or injuries.

I did some simple graphs and charts to get a general idea of where the traffic accidents were occuring. I incorporated pie, bar, and line graphs in my EDA.

Afterwards, I used Tableau to get a more aesthetically pleasing graphic of where the traffic accidents were occuring. I built a simple map to compare where accidents were happening pre-pandemic and post-pandemic.

## Tools
* Python and Pandas for data sampling
* Microsoft Excel for data cleaning, exploratory data analysis, and visualizations
* Tableau for mapping

# Communication

I found that traffic-related deaths and injuries and traffic accidents in general increased by a large margin after the pandemic started. My data for 2021 includes up to the end of September and given the fact we still have three more months left in the year, we can expect traffic accidents and related deaths and injuries to increase even more.

![image](https://github.com/guostan123/business/blob/main/injuries_death_per_year_line.png)

Unsurprisingly, the percentage of traffic accidents in Manhattan had the largest decrease, 5%, where as every other borough experienced an in increase. The 5% decrease in Manhattan can be explained by the mass exodus of people the borough faced at the start of the pandemic.

![image](https://github.com/guostan123/business/blob/main/pre_pandemic_pie.png)

![image](https://github.com/guostan123/business/blob/main/post_pandemic_pie.png)
