# World_Weather_Analysis

## Overview of Analysis

In this challenge, PlanMyTrip Beta testers have suggested that I add the Current Weather Description to the weather data. Next, I'll also add in two input statement to allow Beta testers to filter the travel locations based on their ideal weather preferences. Lastly, with four cities of the Beta testers' choosing, we will use the Google Maps Directions API to...

1. Create a travel route between all four cities AND...
2. Add a marker layer map

## Results

First, using the full extent of the Weather Database, we allowed the user to filter the travel locations. In this specific test, the user gave the following input:

- min_temp: 75°F
- max_temp: 90°F

After cleaning the data and creating the clean_hotel dataframe, we were able to create and display the filtered customer travel destinations map using the gmaps dependency and our Google Maps API key.

Next, we selected the following four cities, all located in Southern India:

1. Kanniyakumari
2. Malpe
3. Narayanpet
4. Kattivakkam

Finally, using the coordinates for each city, we created the following map, which includes the directions, pop-up markers, and corresponding information boxes.

![Travel Map](https://github.com/dharlerjr/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)
![Travel Map Markers](https://github.com/dharlerjr/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)

## Summary
