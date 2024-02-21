# World Weather Analysis

## Overview of Analysis

### Background

PlanMyTrip is a fictional travel technology company that maintains a website which allows users to search for their ideal city to visit and nearby hotel to stay at by filtering on various weather criteria. In this module, Jack, the head of analysis for the UI team at PlanMyTrip, has tasked us with collecting and analyzing city data from over 500 cities around the globe. This data will then allow us to generate insights which will in turn help website users plan their ideal vacation. Here's a breakdown of how we completed this project:

- Generate 1500 random pairs of coordinates and find the nearest to each coordinate pair, if applicable
- Use the OpenWeatherMap API to retrieve current weather data for each city in the generated dataset
- Perform Exploratory Data Analysis (EDA) by
  - Creating scatter plots to compare various features from the weather data, such as Latitude vs. Temperature
  - Computing the correlation coefficient between different pairs of features from the weather data
  - Creating heatmaps using the Google Maps & Places API
- Creating a heatmap which displays city information based on user input 

### Purpose

After completing our initial analysis, PlanMyTrip Beta testers have suggested that I add the Current Weather Description to the weather data. We'll again use two input statements to allow Beta testers to filter the travel locations based on their ideal weather preferences. Lastly, with four cities of the Beta testers' choosing, we will use the Google Maps Directions API to create a travel route between all four cities and use pop-up markers to display each city's information and current weather.

## Results

First, using the full extent of the Weather Database, we allowed the user to filter the travel locations. In this specific test, the user gave the following input:

- min_temp: 75°F
- max_temp: 90°F

After cleaning the data and creating the clean_hotel dataframe, we were able to create and display the filtered customer travel destinations map using the gmaps dependency and our Google Maps API key.

Next, the user selected the following four cities, all located in Southern India:

1. Kanniyakumari
2. Malpe
3. Narayanpet
4. Kattivakkam

Finally, using the coordinates for each city, we created the following map, which includes the directions, pop-up markers, and corresponding information boxes.

![Travel Map](https://github.com/dharlerjr/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)
![Travel Map Markers](https://github.com/dharlerjr/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)

## Summary
All in all, our project was a success. We succeeded in building our dataset, performing our exploratory data analysis, and creating a heatmap to display the user's recommended travel itinerary. Below are a few screenshots displaying further results from our analysis.


