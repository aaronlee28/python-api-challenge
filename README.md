# python-api-challenge
There are two parts to the project. The goal of the first part of the project is to create a Python script to visualize the weather of 500+ cities across the world of varying distances from the equator. Simple Python Library and OpenWeatherMap API are used to accomplish this. A series of scatter plots and linear regressions are used to showcase the relationships between Temperature vs Latitude, Humidity vs Latitude, Cloudiness vs Latitude, and Wind Speed vs Latitude.  

The second part of the project used jupyter-gmaps and the Google Places API to create heat maps that display the humidity for every city from part one of the project. The DataFrame is then narrowed down to find the 'ideal weather condition' using filters, and Google Places API is used to find the first hotel for each city located within 5000 meters of the given coordinates. 

Note: 
OpenWeatherMap API and Google Places API keys are used to run this script. Please use your own API keys and paste them into the api_key.py file. 

