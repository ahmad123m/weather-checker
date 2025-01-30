Weather Prediction App 🌦️
This is a Streamlit-based Weather Prediction App that fetches real-time weather data for any city using the OpenWeatherMap API. It also allows users to download the weather data as a CSV file and visualize the average temperature by city in a bar chart.

Features
Real-Time Weather Data: Get current weather details (temperature, humidity, and weather description) for any city.

Data Export: Download the weather data as a CSV file.

Visualization: View a bar chart of the average temperature for searched cities.

User-Friendly Interface: Built with Streamlit for a clean and interactive UI.

Prerequisites
Before running the app, ensure you have the following installed:

Python 3.7+

Streamlit (pip install streamlit)

Requests (pip install requests)

Pandas (pip install pandas)

Matplotlib (pip install matplotlib)

Setup
Clone the Repository:

bash
Copy
git clone https://github.com/ahmad123m/weather-checker.git
cd weather-app
Install Dependencies:

bash
Copy
pip install -r requirements.txt
Get an API Key:

Sign up at OpenWeatherMap and get your free API key.

Set the API key as an environment variable:

bash
Copy
export OPENWEATHER_API_KEY="your_api_key_here"
Alternatively, you can hardcode the API key in the weather.py file (not recommended for production).

Run the App:

bash
Copy
streamlit run weather.py
Usage
Enter a City Name:

Type the name of the city in the input box (e.g., "London").

Click the Get Weather button to fetch the weather details.

Download Weather Data:

Click the Download Weather Data as CSV button to export the weather data for all searched cities.

View Weather Graph:

Click the Show Weather Graph button to visualize the average temperature for the searched cities.

Example
Input:
City: New York

Output:
Weather Description: Clear sky

Temperature: 15°C

Humidity: 60%

Graph:
A bar chart showing the average temperature for all searched cities.

Screenshots
Weather App Screenshot

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contributing
Contributions are welcome! If you'd like to improve this project, please follow these steps:

Fork the repository.

Create a new branch (git checkout -b feature/your-feature).

Commit your changes (git commit -m 'Add some feature').

Push to the branch (git push origin feature/your-feature).

Open a pull request.

Acknowledgments
OpenWeatherMap for providing the weather data API.

Streamlit for the amazing framework to build interactive web apps.

Contact
For any questions or feedback, feel free to reach out:

Your Name: Muhammad Ahmad

GitHub: ahmad123m

Enjoy using the Weather Prediction App! 🌞🌧️❄️
