Weather Prediction App

Overview

This is a simple Weather Prediction App built using Streamlit and OpenWeatherMap API. It allows users to check the current weather conditions of a city by entering its name. Additionally, users can download weather data as a CSV file and visualize temperature trends using a graph.

Features

Fetch real-time weather data using the OpenWeatherMap API.

Displays temperature, humidity, and weather description.

Stores weather search history in the session state.

Allows users to download weather data as a CSV file.

Provides a graphical representation of the average temperature per city.

Technologies Used

Python

Streamlit

OpenWeatherMap API

Pandas

Matplotlib

Requests

Installation

Clone the repository or download the script.

git clone https://github.com/yourusername/weather-app.git
cd weather-app

Install dependencies:

pip install -r requirements.txt

Set up the API key:

Get an API key from OpenWeatherMap.

Set an environment variable OPENWEATHER_API_KEY with your API key.

Usage

Run the Streamlit app:

streamlit run weather.py

Enter a city name in the input field and click "Get Weather."

Use the available buttons to:

Download the weather data as a CSV file.

View a graph of the average temperature by city.

Screenshots

(Sample screenshots can be added here)

Notes

The script uses an environment variable to store the API key for security purposes. If not set, it falls back to a hardcoded API key.

The app also includes an optional background image (wolfgang-hasselmann-bR_-gllg7Bs-unsplash.jpg). Ensure the image is available in the project directory.

License

This project is open-source and available under the MIT License.

Author

Muhammad Ahmad
