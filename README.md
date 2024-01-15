# Python-API-challenge
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"
Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

## WeatherPy:
In this deliverable, you'll find a Python script to visualize the weather of over 500 cities of varying distances from the equator. It uses the citipy Python library, the OpenWeatherMap API, and problem-solving skills to create a representative model of weather across cities.

Plots to Showcase the Relationship Between Weather Variables and Latitude
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

Computed Linear Regression for Each Relationship
- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude
After each pair of plots, an explanation of what the linear regression is modeling. Describing any relationships noticed and any other findings you uncovered.

## VacationPy:

In this deliverable, you'll find weather data to plan future vacations. Using Jupyter notebooks, the geoViews Python library, and the Geoapify API.
There's code included that imports the required libraries and loads the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.
You'll find a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point scaled by the humidity in each city.

Then a map of locations with the ideal weather conditions of Temperatures between 24 and 20 degrees, wind speeds of 5 to 10, cloudiness of less than 15%, and humidity between 30 to 50.

# Table of Contents:
- [Introduction](#introduction)
  - [WeatherPy](##WeatherPy)
  - [VacationPy](##VacationPy)
- [Usage](#usage)
- [Acknowledgements](#acknowledgemnets)
- [Authors](#authors)

  
# Usage:<a name="usage"></a>
For this app it's necessary to create an API from https://openweathermap.org/api and https://www.geoapify.com/get-started-with-maps-api. Then run files WeatherPy.ipynb  to look at the analysis, and VacationPy.ipynb to look at the hotels in the cities with the best weather. 


# Acknowledgments:<a name="acknowledgemnets"></a>
- supporting documentation from UT Austin The Data Analytics and Visualization Bootcamp at https://git.bootcampcontent.com/University-of-Texas-at-Austin/UTA-VIRT-DATA-PT-08-2023-U-LOLC/-/tree/main

  
# Authors:<a name="authors"></a>
- AC2BARRETO
