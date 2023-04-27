# Python-API-Challenge

## WeatherPy Data Analysis

### Created a Python script in Jupyter Notebooks to visualize the weather of over 500 cities of varying distances from the equator using the citypy Python library, and OpenWeatherMap API. Created a representative model of weather across cities, and included the following:

- Created Plots to Showcase the Relationship Between Weather Variables and Latitude 

- Used the OpenWeatherMap API to retrieve weather data from a list of cities

- Created a series of scatter plots to showcase the following relationships between those cities:

    - Latitude vs. Temperature
    - Latitude vs. Humidity
    - Latitude vs. Cloudiness
    - Latitude vs. Wind Speed

- Computed Linear Regression for Each Above Relationship

- Separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude)

- Created a series of scatter plots that includes linear regression lines, the model's formula, and the r values for each of the following relationships:

    - Southern Hemisphere: Temperature vs. Latitude
    - Northern Hemisphere: Temperature vs. Latitude
    - Northern Hemisphere: Humidity vs. Latitude
    - Southern Hemisphere: Humidity vs. Latitude
    - Northern Hemisphere: Cloudiness vs. Latitude
    - Southern Hemisphere: Cloudiness vs. Latitude
    - Northern Hemisphere: Wind Speed vs. Latitude
    - Southern Hemisphere: Wind Speed vs. Latitude

Additionally, included a brief analysis of each relationship pair.

## VacationPy Data Analysis

### Created a Python script in Jupyter Notebooks to plan future vacations (*wow!*) using the geoViews Python library, and the Geoapify API. Created map visualizations, and included the following:

- Created a map that displays a point for every city from WeatherPy, with the size of the point reflecting the humidity in each city

- Narrowed down the city list to find my ideal weather conditions:

    - A max temperature lower than 23 degrees but higher than 12
    - Wind speed less than 5 m/s
    - Cloudiness less than 5

- For each city with this criteria, used the Geoapify API to find the first hotel located within 10,000 meters of the coordinates

- Added the hotel name and the country as additional information in the hover message for each city on the map
