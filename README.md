# Weather and Vacation Analysis

## Overview
This repository contains a two-part Python project using APIs and data visualization to analyze weather patterns and plan vacations based on ideal weather conditions.

## Features
### Part 1: WeatherPy
- Retrieves weather data from over 500 cities worldwide using the OpenWeatherMap API.
- Uses citipy to determine the nearest city based on randomly generated latitude and longitude.
- Creates scatter plots to analyze relationships between latitude and weather variables:
  - Latitude vs. Temperature
  - Latitude vs. Humidity
  - Latitude vs. Cloudiness
  - Latitude vs. Wind Speed
- Computes linear regression for each weather variable in both hemispheres to understand trends.
- Provides statistical insights and interpretations based on regression analysis.

### Part 2: VacationPy
- Uses weather data to identify locations that meet specific weather conditions.
- Leverages the Geoapify API to find nearby hotels within 10,000 meters of selected locations.
- Creates an interactive map displaying:
  - City locations based on weather data
  - Humidity levels visualized by point size
  - Hotels in selected vacation spots with country and hotel names in hover messages.

## Dependencies
This project requires the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- requests
- json
- geoViews
- citipy

## Results & Insights

Clear relationships exist between latitude and temperature, confirming the general expectation that temperatures rise near the equator.

Humidity, cloudiness, and wind speed show weak correlations with latitude, offering insights into regional weather patterns.

The VacationPy analysis successfully identifies vacation spots based on specific weather criteria and finds nearby accommodations.

## Author
### Logan Dameron

## For Educational Purposes only
