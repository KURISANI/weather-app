# ☁️ Weather App – Python Desktop Application

A simple desktop weather application built with Python. Enter any city and get real-time temperature, weather description, and an emoji representing current conditions.

## 📌 What it does

- Fetches live weather data from OpenWeatherMap API
- Displays temperature in Celsius and Fahrenheit
- Shows a weather description (e.g., "clear sky", "light rain")
- Shows an emoji icon based on weather conditions (☀️, 🌧️, ⛈️, etc.)
- Handles errors gracefully (invalid city name, no internet, API issues)

## 🛠️ Tools & Technologies

- **Python 3** – core programming language
- **PyQt5** – for the graphical user interface (GUI)
- **Requests** – to call the weather API
- **OpenWeatherMap API** – weather data source

## 📁 Project Structure
weather-app/
├── weather_app.py # Main application code
└── README.md # This file


## 🚀 How to Run

1. **Clone or download this repository**

2. **Install required packages**
   ```bash
   pip install pyqt5 requests

python weather_app.py

📸 What it looks like
<img width="417" height="537" alt="weather app" src="https://github.com/user-attachments/assets/7a3c12dc-3638-4a60-8400-aac58896a088" />

🔑 API Key Note
The app includes a free OpenWeatherMap API key. If you want your own key:

1. Sign up at openweathermap.org
2. Replace the api_key variable in the code with your new key

👨‍💻 Author
McCauley Mabedhle
Data Scientist | Data Engineer
GitHub • LinkedIn

📈 What I learned

- Building desktop GUIs with PyQt5
- Working with REST APIs and JSON data
- Error handling for network and API failures
- Mapping weather codes to user-friendly icons
