---
layout: page
title: Project Overview
subtitle: Why Bikeshare?
---

Bikeshare systems are an alternative form of public transport to traditional buses and subways which allow users to pick-up and drop-off shared bikes at specific stations around the city. The use of the bikeshare system has been increasing, making it an important feature to consider in the city's complete transport system. In the last year however it has begun to decrease; an improvement of the system may be able to bring usage back up. Biking is both more environmentally friendly and healthier than automobiles, and incorporating this system is a benefit to the city's inhabitants. We thus want to analyse the system to see how people currenlty use the system and then find improvements to maximize and encourage the use of this beneficial form of transport. We especially want to analyse it with respect to its interactions and incorportation with other tranport infrastructures. 


### What is the BIXI bike system?
BIXI bike is a bikeshare system in Montreal, much like other bikeshare systems around the world. We first wanted to understand however how the system was being used by users and how it was set up. Where do people like using the bikes? What are they using them for? What factors could effect our results?  

[Learn more](bixi.md)

### How safe is it?
One of the main concerns of people riding on bikes in cities is the safety. You are sharing the road with many drivers who may or may not be looking out for bikes. Many people may simply be too afraid to bike along a busy road downtown. Their savior: bike paths. We analysed the density of bike paths across the city to see if people were more likley to go between stations which had a safe route. If this is a major factor, creating more bike lanes between the most popular stations could be a benefit to bikers.

[Learn more](paths.md)

### By Bike or by Bus?
We all want to try and find the fastest way to get from A to B. We also don't want to crowd into a cramped bus with 60 other people. What makes us decide whether to take the bus or metro versus go on a bike? Does the bikeshare help fill the gaps where the buses don't go often? Or do we use it in parallel with the bus lines to have a more pleasant, or even still faster, commuting experience? 

[Learn more](buses.md)

### Will I arrive to work soaking wet?
Here we look at the weather and how that effects the use of bikes. What weather factors increase or decrease bike use? We can't change the weather, but can we modify the system to make biking more friendly year round?

[Learn more](weather.md)

## The Data
For our analysis we worked with 4 different datasets:
1. BIXI Bikeshare trips (type = .csv, files = data for each year and month, station locations and codes for each year, 
link : https://montreal.bixi.com/en/open-data)
2. Montreal weather data (type = .csv, files = data for each day, temperature, precipitation, snow and wind max speed, 
link : https://climat.meteo.gc.ca/historical_data/search_historic_data_f.html)
3. Public transport schedule (type = , files =  )
4. Bike paths (type = .geojson, files = data that contains bikepath location and types, 
link : http://donnees.ville.montreal.qc.ca/dataset/pistes-cyclables)

## A brief summary 
Analysing geographical data is difficult. We did not find a link between the presence of bike paths and bike use although it may be due to the method of analysis. We did however manage to reveal a link between metros and bikes. We also managed to confirm an evidence people don't like to bike in cold weather. All these informations may be used by organizations to improve and adapt infrastructure.
