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

## Available API Requests

This Postman collection includes a series of test cases for the OpenWeatherMap API, demonstrating how to handle different scenarios. Below are the requests included in the collection:

1. **GET with Valid API key**: Tests the API response when a valid API key is provided.
2. **GET with Invalid API key**: Tests how the API responds when an invalid API key is provided.
3. **GET with Missing API key**: Tests the behavior when the API key is missing.
4. **GET weather by city**: Fetches weather information based on the city name.
5. **GET weather by city + units (Temperature in Celsius)**: Fetches weather data for a city with the temperature in Celsius.
6. **GET weather by city + lang**: Fetches weather data for a city, specifying the language for the response.
7. **GET weather by coordinates**: Fetches weather data based on geographical coordinates (latitude and longitude).
8. **GET forecast**: Fetches the weather forecast for a given location.
9. **GET Invalid city name**: Tests how the API handles an invalid city name.
10. **GET Missing required param**: Tests how the API responds when a required parameter is missing.
11. **GET Invalid coordinates**: Tests how the API handles invalid geographic coordinates.

These test cases are designed to ensure the API handles different input scenarios effectively.
