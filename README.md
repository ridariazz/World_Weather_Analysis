# World_Weather_Analysis

## Overview

For this project, we looked at different weather patterns around the world to see which places travelers would like to book their next trip. We allowed travelers to filter their weather preferences to also identify nearby travel destinations and hotels. We chose 4 cities that are nearby to create a travel itinerary. Using Google Maps API, we created a travel route between our chosen 4 cities as well as a marker layer map.

## Weather Database 

We generated a set of 2,000 random latitudes and longitudes, retrieved the nearest city and performed an API call with the OpenWeatherMap. We created the DataFrame that we will use for the other two parts of our analysis and saved it as a CSV file into our weather_database folder. 

We pulled data from 702 cities with categories which will allow our travelers to pick their next travel destination:

- Maximum Temperature
- Humidity
- Wind Speed
- Current Weather Description
- Cloudiness

