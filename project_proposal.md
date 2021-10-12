# Question and Need
One of the major focal points of Mayor Bill de Blasio's career as New York City mayor is to reduce the occurence of traffic accidents on city roads. Vision Zero is de Blasio's traffic initiative in an attempt to eliminate all traffic fatalities and severe injuries. Despite heavy investment in public awareness campaigns towards Vision Zero, traffic accidents and fatalities have been at an all time high.

Since the pandemic started, statistic after statistic has show that Vision Zero has been a total failure as more people took up cycling and walking. Even the de Blasio administration has acknowledged the shortcomings of Vision Zero. The city is on pace to record its highest number of traffic deaths in a calendar year since 2014, the year de Blasio took office and launched his Vision Zero program with the goal of reducing fatal car crashes.

The client, the New York City Department of Transportation (NYCDOT) is the main organization responsbile for rolling out Vision Zero. By gathering data on the occurences of traffic accidents and then visualizing them, I can inform the NYCDOT on where they should focus their efforts and if applicable, install new infrastructure. This will hopefully help reduce the number of incidents around the city's most at-risk areas.

# Data Description
I will be using motor vehicle collision data from NYC OpenData which is publicly available and supplied by the New York City Police Department (NYPD). It's important to note that this list only contains data from accidents that have been accompanied with a police report, so it's safe to assume that there are many more accidents at high-risk areas that have gone unreported.

Features from the dataset that I'll be expecting to work with are longitude and latitude of accidents and number of persons killed.

# Tools
Because the dataset is extremely large (~1.8 million rows), I plan to use Python for logistical efficiency. I'll conduct initial data cleaning to focus on the time period that I'm interested in (since the pandemic started), before exporting the data back out to Excel as a CSV for further data exploration. The final touches that involve visualization will be done with Tableau.

# MVP Goal
The MVP is to find out which areas around the city have the highest concentration of traffic accidents.
