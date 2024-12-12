# WeatherInsight
This Python script allows you to get the current weather information for a specific city. It uses the OpenWeatherMap API to fetch weather data, and then it provides two key pieces of information: the weather description (like clear, rainy, etc.) and the temperature in Celsius.

## How It Works

1. The script prompts the user to input a city name.
2. It then sends a request to the OpenWeatherMap API, which returns the weather data for that city.
3. The response from the API is parsed to extract the weather description and the temperature, which is initially provided in Kelvin.
4. The script converts the temperature from Kelvin to Celsius and displays both the weather description and the temperature to the user.

## Key Features

- Weather description (e.g., clear sky, rain, etc.)
- Temperature in Celsius (converted from Kelvin)
- Simple command-line interface

## Requirements

To run the script, you will need:

- Python 3.x
- The `requests` library, which can be installed using `pip`
- An API key from OpenWeatherMap

The script is designed to be simple and easy to use, providing basic weather data for any city.
