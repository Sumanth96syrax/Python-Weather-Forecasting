# Weather App

## Overview

The Weather App is a web-based application developed in Python using Streamlit. It allows users to check the current weather in any city by retrieving real-time data from the OpenWeatherMap API. The application displays weather information including description, temperature, humidity, and pressure.

## Features

- **Weather Information:** Fetch and display current weather details for a user-specified city.
- **Temperature Conversion:** Convert temperature from Kelvin to Celsius.
- **Error Handling:** Gracefully handle errors for invalid city names and API request issues.

## Requirements

- Python 3.x
- `requests` library
- `streamlit` library

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/weather-app.git

Install Dependencies:
Install the required Python libraries using pip:
pip install requests streamlit

## Get an API Key:
Sign up at OpenWeatherMap and obtain a free API key. Replace "fc64bedf5035bd436bd6fd60e21ca3ff" in the code with your actual API key.

## Usage
Run the Application:
Start the Streamlit application using:

- streamlit run app.py

Open your web browser and go to the address provided by Streamlit (usually http://localhost:8501).
Enter the name of the city in the text input field.
Get Weather Information:

Click the "Get Weather" button to fetch and display the current weather details for the entered city.
