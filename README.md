# python-api-challenge1

# Part 1: WeatherPy
A python script was created to visualize the weather of 500+ cities of varying distances from the equator. Citipy python library and the OpenWeatherMap API were used to help create a representative model of weather across various cities. Scatter plots of the Northern and Southern Hemisphere were generated to show the relationships between latitude versus temperature, latitude versus humidity, latitude versus cloudiness, and latitude versus wind speed. Further, a linear regression was preformed for each relationship and the r values and the model's formulas were calculated. 

# Part 2: VacationPy
The geoViews Python library, Geoapify API, and jupyter notebook were used to plan future vacations. Map visualizations were created for each city in the city_data_df DataFrame. Next, the city_data_df was narrowed down to find the ideal weather condition. A hotel_df Dataframe was created to store the city, country, coordinates, and humidity. The Geoapify API was used to find the first hotel that was located wihin 10,000 meters from the  coordinates. The hotel name and country was included among additonal information in the hover message for each city on the map.  
