# Weather Prediction App

## Overview
This is a simple Weather Prediction App built using Streamlit and OpenWeatherMap API. It allows users to check the current weather conditions of a city by entering its name. Additionally, users can download weather data as a CSV file and visualize temperature trends using a graph.

## Features
- 🌍 Fetch real-time weather data using the OpenWeatherMap API.
- 🌡️ Displays temperature, humidity, and weather description.
- 📌 Stores weather search history in the session state.
- 📥 Allows users to download weather data as a CSV file.
- 📊 Provides a graphical representation of the average temperature per city.

## Technologies Used
- 🐍 Python
- 🎨 Streamlit
- ☁️ OpenWeatherMap API
- 📝 Pandas
- 📉 Matplotlib
- 🔗 Requests

## Installation
1. 📥 Clone the repository or download the script.
   ```bash
   git clone https://github.com/ahmad123m/weather-checker.git
   cd weather-app
   ```
2. ⚙️ Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. 🔑 Set up the API key:
   - Get an API key from [OpenWeatherMap](https://openweathermap.org/).
   - Set an environment variable `OPENWEATHER_API_KEY` with your API key.

## Usage
1. 🚀 Run the Streamlit app:
   ```bash
   streamlit run weather.py
   ```
2. 🌆 Enter a city name in the input field and click "Get Weather."
3. 🛠️ Use the available buttons to:
   - 📂 Download the weather data as a CSV file.
   - 📉 View a graph of the average temperature by city.


## Notes
- 🔒 The script uses an environment variable to store the API key for security purposes. If not set, it falls back to a hardcoded API key.
- 🖼️ The app also includes an optional background image (`wolfgang-hasselmann-bR_-gllg7Bs-unsplash.jpg`). Ensure the image is available in the project directory.

## License
📝 This project is open-source and available under the [MIT License](LICENSE).

## Author
👤 Muhammad Ahmad

