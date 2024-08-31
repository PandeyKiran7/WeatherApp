WeatherApp
Description
WeatherApp is a simple and intuitive web application that allows users to search for the current weather conditions and a 5-day forecast for any city in the world. The app also provides the functionality to use the user's current location to display the weather data.

Features
Search by City: Enter the name of any city to retrieve current weather data, including temperature, wind speed, and humidity.
5-Day Forecast: View a 5-day weather forecast with detailed information on temperature, wind, and humidity for each day.
Current Location: Use the "Use Current Location" button to automatically fetch and display the weather data for your current geographical location.
Technologies Used
HTML5: Structure of the web app.
CSS3: Styling and layout of the web app.
JavaScript: Fetching weather data and adding interactivity.
OpenWeatherMap API: Provides the weather data for the application.
Installation
Clone the Repository
To get started, clone this repository to your local machine using:

bash
Copy code
git clone https://github.com/PandeyKiran7/WeatherApp.git
Open the Project
Navigate to the project folder and open the index.html file in your preferred web browser to view the app.

Usage
Search for a City:

Enter the name of the city you want to search for in the input field and click the "Search" button. The current weather and a 5-day forecast will be displayed.
Use Current Location:

Click the "Use Current Location" button to allow the app to access your location and display the weather data for your current position.
View Weather Details:

The current weather section shows the city name, temperature, wind speed, and humidity.
The 5-day forecast section displays a daily breakdown of these details.
API Key Configuration
To use this app with the OpenWeatherMap API, you need to add your API key to the JavaScript file.

Go to OpenWeatherMap and sign up to get a free API key.
In your script.js file, replace 'YOUR_API_KEY' with your actual API key.
javascript
Copy code
const apiKey = 'YOUR_API_KEY';
Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any feature requests, bug fixes, or improvements.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments
Special thanks to OpenWeatherMap for providing the weather data.
Thanks to the 
