# WeatherAppCLI

A simple command-line tool to fetch and display weather information for any location using the OpenWeather API.

## Features
- Get current weather conditions: temperature, humidity, wind speed, and weather description.
- View a daily weather summary including high and low temperatures.
- Receive government-issued weather alerts for severe conditions.

## Requirements
- Python 3.6 or later.
- OpenWeather API key (sign up for free [here](https://openweathermap.org/)).

## How to Use
### Clone the Repository
git clone https://github.com/yourusername/WeatherAppCLI.git
cd WeatherAppCLI
## Install Dependencies
The script does not require any external libraries beyond the Python standard library. Just ensure you have Python installed.

## Run the Script
Run in Terminal (CLI):

python weather_app.py
You will be prompted to enter the latitude and longitude.

Run in Jupyter Notebook/Colab:

Just run the script, and it will default to lat=33.44 and lon=-94.04.
## Example Usage
## Input:

Enter latitude: 33.44
Enter longitude: -94.04
## Output:

Fetching weather data...

🌤 Current Weather:
   Condition: Broken clouds
   Temperature: 18.5°C (Feels like 17.8°C)
   Humidity: 65%
   Wind Speed: 3.5 m/s

📅 Today's Weather Summary:
   Expect a day of partly cloudy with rain
   Day Temperature: 20.5°C
   Min Temperature: 15.2°C
   Max Temperature: 21.8°C

✅ No weather alerts.
## Notes
Replace the YOUR_DUMMY_API_KEY placeholder in the script with your own API key from OpenWeather.
If running in Jupyter/Colab, default values for latitude (33.44) and longitude (-94.04) are used.
License
This project is licensed under the MIT License. Feel free to use and modify it.
