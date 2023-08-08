# python-api-challenge
Module 6 Challenge Assignment
Python APIs

## Contributor: Katy Yelle
### Overview
For this challenge there are two folders- WeatherPy and output_data.  In the WeatherPy folder you will find two Jupyter Notebook scripts: WeatherPy.ipynb and VacationPy.ipynb.  The output_data folder contains results from running the WeatherPy script which is then used to run the VacationPy script.

#### Parts
WeatherPy
This script pulls over 500 random cities and then creates plots to show the relationship of different weather variables (temperature, humidity, cloudiness and wind speed) and latitude.  Linear regressions are run for each of these weather variables for each hemisphere.

VacationPy
This script uses the csv file created by WeatherPy as a starting point and displays a map of these cities with marker size being based on humidity. Thanks to Learning Assistant Robert Perron for helping me ensure the correct installations were in place of the maps to display (cartopy, geoviews, pyproj) Then it filters to only show cities with what I determined as ideal weather conditions (no clouds, low humidity and a temperature between 70-85 degrees Fahrenheit which is converted to Celsius in the script).  The script then locates the closest hotels in each of the cities in the ideal weather dataframe and creates a map of each of the ideal weather cities. Thanks to Learning Assistant Deborah Aina for helping me troubleshoot the iterrows code so this could run correctly. When you hover over each point on the map it will include the longitude, latitude, hotel name and country. 