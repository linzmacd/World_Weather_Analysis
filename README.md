# World Weather Analysis

## Purpose

The purpose of this project was to retrieve data in JSON format from external APIs and generate heatmaps, location markers, and route maps using the Google Maps Interface.

## Deliverable 1: Retrieve global weather data

We started by generating 2000 random latitude and longitude pairs and used the OpenWeatherMap API to locate the corresponding cities and their current weather conditions. The retrieved data was stored in a new DataFrame.

## Deliverable 2: Create Customer Travel Destinations Map

We used input statements for users to narrow down potential vacation destinations based on their weather preferences and generated a map with markers showing hotels at each respective destination (found by using a Google Places API Nearby Search) along with the current weather conditions.

<img src="https://github.com/linzmacd/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG">
 
## Deliverable 3: Create a Travel Itinerary

We then selected 4 destination cities in the same vicinity and created a travel itinerary map connecting the cities (generated by using the gmaps directions plugin for jupyter notebook) and a marker map with hotel destinations in each city.

<img src="https://github.com/linzmacd/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG" width=50% height=50%> <img src="https://github.com/linzmacd/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG" width=50% height=50%>