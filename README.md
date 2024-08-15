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
   git clone https://github.com/username/weather-information-app.git
   cd weather-information-app
2. Add your API key in WeatherService.java.
3. Compile the application:
	javac -cp .;lib\javafx-sdk-17.0.2\lib\* -d out src\*.java
4. Run the application:
	java -cp out;lib\javafx-sdk-17.0.2\lib\* MainApp


## Setup
	>> Enter a city name or coordinates to get the weather data.
	>> Use the GUI to view weather details and switch units.
	>> Access recent searches from the history tab.
	
## License
	This project is licensed under the MIT License.


## Author
	Olif Sahara

