# python-api-challenge
Module 6 Challenge, two Python API challenges

## WeatherPy

### Purpose

To create a Python script to visualize the weather of over 500 cities of varying distances from the equator and to create a representative model of weather across cities.

### Overview

Part 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude. Create a series of scatter plots to showcase the following relationships:

- [x] Latitude vs. Temperature

- [x] Latitude vs. Humidity

- [x] Latitude vs. Cloudiness

- [x] Latitude vs. Wind Speed

Part 2: Compute Linear Regression for Each Relationship. Create the following Linear Regression plots:

- [x] Northern Hemisphere: Temperature vs. Latitude

- [x] Southern Hemisphere: Temperature vs. Latitude

- [x] Northern Hemisphere: Humidity vs. Latitude

- [x] Southern Hemisphere: Humidity vs. Latitude

- [x] Northern Hemisphere: Cloudiness vs. Latitude

- [x] Southern Hemisphere: Cloudiness vs. Latitude

- [x] Northern Hemisphere: Wind Speed vs. Latitude

- [x] Southern Hemisphere: Wind Speed vs. Latitude

### Results

For results see the output_data and WeatherPy.ipynb files.

![image](https://github.com/saganaga/python-api-challenge/assets/120337916/87dd9f94-19ff-4c02-93c8-e1b593610d82)

![image](https://github.com/saganaga/python-api-challenge/assets/120337916/32840c4d-1a2f-4cd5-aaf7-a7baa12c55ed)

![image](https://github.com/saganaga/python-api-challenge/assets/120337916/d0afb2ed-43d2-48b3-b897-a73959ee19cc)

![image](https://github.com/saganaga/python-api-challenge/assets/120337916/fbcebf7a-92e8-4427-8e33-67fb6fc64dd5)

### Summary

Plots show that getting closer to the equator the temperature rises, but no changes of any significance for humidity, cloudiness and wind speed.

## VacationPy

### Purpose

To use weather data skills to plan future vacations.

### Overview

Use the Geoapify API and the geoViews Python library to create map visualizations. Complete the following steps:

- [x] Create a map that displays a point for every city in the city_data_df DataFrame

- [x] Narrow down the city_data_df DataFrame to find your ideal weather condition

- [x] Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity

- [x] For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates

- [x] Add the hotel name and the country as additional information in the hover message for each city in the map

### Results

For results see the VacationPy.ipynb file.
