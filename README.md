# Module 6 - API - Challenge

## Location of files
This assignment has two parts. Part 1 is a WeatherPy exercise and part 2 is VacationPy exercise. Both of the exercises have been stored in the GitHub folder called **'main_code'**. For convenience, the output for part 1 has been stored in **'output_data'** rather than inside the 'main_code' folder.  The **'research'** folder has a .json output file, which was used to understand the hierarchy of information and to know where specific returned information from the API can be extracted.

## WeatherPy Exercise
In this exercise, the numpy module was used to generate random latitude and longitude coordinates. These were, in turn, used in the **citypy** library to find the nearest city in the coordinates.

In this exercise, we continued to use the numpy-generated coordinates; however, using the exact city coordinates may have been another way to do this exercise. The names of the cities could have been queried using Geoapify to find the exact city coordinates.

The OpenWeather API was used to extract the weather information for each city and add it to the 'city_data' data frame. The output data frame was saved as a .CSV file in the 'output_data' folder.

Using the data frame, a series of scatter plots were completed using the matplotlib module in Python. A regression analysis was also completed for each of these scatter plots. As part of the regression analysis, the regression line was plotted, and the equation of the line was annotated to the chart. The R and R squared values were calculated and displayed. A brief discussion about the linear relationship of the set of scatter plots for the northern and southern hemispheres has been provided.

## VacationPy Exercise
In this exercise, the data frame created in the Weatherpy exercise was used to plot the cities on a world map with the size of the dots representing the humidity.  The 'Holoviews' module was used for these plots.

A second data frame called 'hotel_df' was created using the primary cities data frame to include cities with ideal holiday conditions (personal preferences). This new data frame was used to locate the closest hotel in that area using the Geoapify API. Any location that did not return a hotel name within a 10,000-meter radius was dropped. 

Using the locations in the 'hotel_df,' a new map was created showing the location, with the hotel name and the country in the hover information.

## API Keys
Please note both the [OpenWeatherMap API](https://openweathermap.org/api) and the [Geoapify API](https://www.geoapify.com/) require keys. Please use the hyperlinks for more information.
