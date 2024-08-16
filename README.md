
Here is the updated README file with the new features included:

Weather App ☔
Weather App is a simple web application built with React and Vite that allows users to search for a city and retrieve the current weather conditions and forecast.

Getting Started 💻
To run this application locally, follow these steps:

Prerequisites
Make sure you have Node.js and npm installed on your machine.

Installation
Clone the Repository:



Navigate to the Project Directory:

bash
Copy code
cd weather-app
Install Dependencies:

bash
Copy code
npm install
Run the Application:

bash
Copy code
npm run dev
This will start the local development server.

Features ✨
1. Daily Weather Summary
The app includes a feature to generate and store a daily weather summary with the following details:

Roll up the weather data for each day: Collect weather data at regular intervals and aggregate it daily.

Calculate daily aggregates:

Average Temperature: Computes the average temperature for the day.
Maximum Temperature: Tracks the highest temperature recorded during the day.
Minimum Temperature: Tracks the lowest temperature recorded during the day.
Dominant Weather Condition: Determines the most frequent weather condition (e.g., sunny, cloudy, rainy) based on the hourly data. The dominant weather condition is selected based on the mode of the weather conditions reported throughout the day.
Store Daily Summaries: These summaries are stored in a database or persistent storage for further analysis and can be retrieved later for review.

2. Search and View Weather Data
Search for a City: Enter the city name in the search bar to get the current weather and forecast.
Current Location: Click on the "Current Location" button to fetch weather data based on your location.
Temperature Units: Toggle between Fahrenheit and Celsius using the button on the interface.
About the Developer 👩‍💻
This application was developed by Ishika. If you have any questions or suggestions, feel free to reach out.