# Python-API-Challenge

This challenge uses API keys to locate weather and geographical data. In WeatherPy, random cities' weather data are found on Open Weather Map using the Numpy random function to generate over 500 latitude and longitude coordinates. Data is obtained and compared on max temperature, humidity, cloudiness, and wind speed. The hemispheres are then split and plots are generated for each hemisphere with a linear regression equation. Based on the linear regression, relationships are inferred and described below each pair of plots. 

VacationPy takes the data obtained in WeatherPy and finds, from the city data obtained, generates a Google Maps humidity heat map of all coordinates found in the city data. Then, the code finds the places with the most ideal weather in the data frame- temperatures of between 70 and 80 degrees, zero cloudiness, and wind speeds of less than 10 mph. The first hotel within 5000 meters of the coordinates is documented in the data frame and geographical markers of each hotel and city identified with ideal weather conditions are placed on the humidity map. 

GRADER: Please be sure to insert your own API keys. 
