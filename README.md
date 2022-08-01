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

## Vacation Search 

Next, we created a DataFrame and depicted the preferences of travel destinations based on the above categories on a marker layer map with pop-up markers.

*Figure 1*

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/106577074/182102758-7f2b26f1-6458-42ad-bc17-31747e172c5a.png)

## Vacation Itinerary 

Finally, to create the hotel maps, we used Google Directions API to create a travel itinerary that shows the route between four chosen cities from the customer's possible travel destinations. 

Our 4 chosen cities are:

- Griffith
- Bud
- Hamilton
- Ingham

Travel method: driving 

*Figure 2: driving route for our 4 cities*

<img width="660" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/106577074/182103522-03805949-4bb5-420a-8a35-ba3882391b64.png">

*Figure 3: hotels for our 4 cities*

<img width="726" alt="weatherpy_travel_map_markers" src="https://user-images.githubusercontent.com/106577074/182103785-5175dedb-8da7-4db3-bab3-502d696d465e.png">

<img width="636" alt="weatherpy_travel_map_markers_2" src="https://user-images.githubusercontent.com/106577074/182103828-c6d1dcaf-4e30-410a-ad42-542d367de3c5.png">

<img width="652" alt="weatherpy_travel_map_markers_3" src="https://user-images.githubusercontent.com/106577074/182103866-6da297f1-94ff-43cd-bbc8-fba30d909b84.png">

<img width="665" alt="weatherpy_travel_map_markers_4" src="https://user-images.githubusercontent.com/106577074/182103906-a35e13e1-1a7d-4353-a3c8-df5235c9350b.png">
