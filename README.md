# python-api-challenge
This challenge uses the citypy Python Library, OpenWeather Map API and Geoapify API to answer do an analysis on weather trends and to identify ideal vacation destinations based on weather and find hotels in those destinations. 
1. WeatherPy visualizes a dataset of 500 cities, and creates a series of visualizations exploring the relationship of Latitude with Temperature, Humidity, Cloudiness & Wind Speeds, including computing a Linear Regression for each.
2. VacationPy takes the dataset from WeatherPy and narrows it down to ideal weather conditions through filtering based on max temperature range, wind speed & cloudiness level. It then uses the Geoapify API to find the closest hotel for each of these destinations, and then visualizes it on a map. 
