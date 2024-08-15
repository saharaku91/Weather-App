# Weather Information App

## Overview
The Weather Information App is a Java-based application that provides real-time weather updates.
It features a user-friendly GUI developed using JavaFX and integrates with the OpenWeatherMap API to fetch weather data.

## Features
- Real-time weather updates for any location
- User-friendly GUI with JavaFX
- Displays temperature, humidity, wind speed, and weather conditions
- Short-term weather forecast
- Unit conversion between Celsius and Fahrenheit
- Error handling for invalid inputs and failed API requests
- History tracking of recent searches
- Dynamic backgrounds based on the time of day

## Requirements
- Java Development Kit (JDK) 8 or higher
- JavaFX library
- Internet connection
- Weather API key from [OpenWeatherMap](https://openweathermap.org/)

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/saharaku91/Weather-App.git
   cd WeatherApp
2. Add your API key in WeatherService.java.
3. Open CMD.exe in Windows and compile the application:
   	javac --enable-preview -source 22 -d bin -cp "src/main/resources;lib/*" src/main/java/com/weatherapp/*.java
4. Run the application:
   	java --enable-preview -cp "bin;src/main/resources;lib/*" com.weatherapp.Main


## Setup
>> Enter a city name or coordinates to get the weather data.
>> Use the GUI to view weather details and switch units.
>> Access recent searches from the history tab.
	
## License
This project is licensed under the MIT License.


## Author

Olif Sahara

