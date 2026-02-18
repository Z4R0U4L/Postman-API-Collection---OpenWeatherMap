# Postman API Collection - OpenWeatherMap

This repository contains a Postman collection to interact with the OpenWeatherMap API. The collection allows you to test various API endpoints for fetching weather data.

## Files Included

- **openweathermapcollection.json**: The Postman collection file for interacting with the OpenWeatherMap API.
- **openweathermapenvironment.json**: A Postman environment file to set variables such as API keys and other parameters.
- **API test practice-2026-02-14-14-18-16-488-0.html**: The HTML file containing the results of the API tests.

## How to Use

1. **Import the Collection**:
   - Open Postman and click on **Import** in the top-left corner.
   - Choose **Upload Files** and select the `openweathermapcollection.json` file from this repository.
   - You will also need to import the environment file (`openweathermapenvironment.json`) in Postman to use the predefined variables.

2. **Set Up API Key**:
   - Make sure to replace the `API_KEY` variable in the Postman environment with your personal OpenWeatherMap API key.

3. **Run the Tests**:
   - Use Postman to execute the requests in the collection. You can test different weather endpoints by running the corresponding API requests.
   - The results of the test runs are documented in the `API test practice-2026-02-14-14-18-16-488-0.html` file. You can open this file in any browser to view the test execution results.

## Example Requests

Here are a few examples of the requests included in the collection:
- **Current Weather Data**: Fetches the current weather information for a given city.
- **Forecast Weather Data**: Fetches the forecast weather information for the next 5 days.
  
