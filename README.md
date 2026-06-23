# Weather Dashboard

A modern, responsive web application that provides real-time weather information and hourly forecasts. Built with HTML, CSS, and Vanilla JavaScript, this project demonstrates clean UI design, RESTful API integration, and geolocation capabilities.

## Features

- **Current Weather Data**: Displays the current temperature, weather conditions, and corresponding dynamic weather icons.
- **Hourly Forecast**: Provides a detailed, scrollable hourly forecast for the current location.
- **City Search**: Allows users to search for weather details of any city globally.
- **Geolocation Support**: Automatically fetches weather data for the user's current location using the browser's Geolocation API.
- **Error Handling**: Displays user-friendly error messages when a location is not found or a network error occurs.
- **Responsive Design**: Adapts seamlessly to different screen sizes for a great mobile and desktop experience.

## Technologies Used

- **Frontend**: HTML5, CSS3, Vanilla JavaScript (ES6+)
- **API**: [WeatherAPI](https://www.weatherapi.com/) for real-time weather data
- **Icons**: Material Symbols / Custom SVG icons

## Setup and Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd weatherapp
   ```

2. **Obtain an API Key:**
   - Sign up for a free account at [WeatherAPI](https://www.weatherapi.com/signup.aspx).
   - Navigate to your dashboard and generate/copy your API key.

3. **Configure the API Key:**
   - Open `script.js` in your preferred text editor.
   - Locate the `API_KEY` variable at the top of the file and replace `'YOUR-API-KEY-HERE'` with your actual API key.

4. **Run the Application:**
   - Simply open the `index.html` file in any modern web browser. No local server is strictly required, though you can use tools like VS Code Live Server for a better development experience.

## Usage

- Upon loading, the application may prompt for location access to display weather for your current area.
- Alternatively, use the search bar at the top to enter a city name and hit "Enter" to view weather data for that specific location.
- Click the location icon next to the search bar at any time to revert to your local weather.