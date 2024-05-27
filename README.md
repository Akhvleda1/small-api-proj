Simple Weather API
This Python script fetches weather information for a specified city from the OpenWeatherMap API and stores it in a SQLite database. It also displays a notification with the current weather temperature.

-Usage
1. Run the script WeatherAPI.py.
2. Enter the name of the city when prompted.
3. The script will fetch weather data, store it in a database, and display a notification with the current temperature.

-Dependencies
requests: Used for HTTP requests to the OpenWeatherMap API.
win11toast: Used for displaying toast notifications on Windows.

-Configuration
Replace the key variable with your OpenWeatherMap API key.
The SQLite database is created in the current directory with the name weather.sqlite.
