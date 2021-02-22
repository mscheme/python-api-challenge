# python-api-challenge
This repository contains work related to the data analytics boot camp API homework assignment
See the instructions in the HW_instructions.md

The WeatherPy folder contains a jupyter notebook, output csv, and output plotted figures.
- Use numpy and ranges to first create a list of random latitudes and longitudes.
- Use citipy to determine the city name using the random latitudes and longitudes.
- Export the city dataframe as a csv file
- Use the OpenWeather API to generate temperature, humidity, cloudiness, and wind speed
- Use the data returned to generate plots against latitude
- Create Linear Regressions to analyze the data

The VacationPy folder contains a jupyter notebook.
- Use the exported city dataframe
- Create a heatmap from the city dataframe locations with humidity as the weight
- Reduce the number of rows in the dataframe based on provided values (range of temperature, wind, clouds)
- Use the reduced dataframe and the Google Places API to search for a hotel in the city
- Store the hotel in the dataframe
- Create a marker layer for the map that displays the hotel name, city, and country
