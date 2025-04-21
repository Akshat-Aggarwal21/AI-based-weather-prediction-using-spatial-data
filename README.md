# AI-Based Real-Time Weather Forecasting App

This project is a Streamlit-powered web application that uses deep learning models to predict the next day's weather for any given city. It leverages real-time data from the OpenWeatherMap API and supports voice input, heatmaps, AI ensemble forecasting, error visualizations, and more.

## Features

- Real-time weather data from OpenWeatherMap API
- Voice-based city input using SpeechRecognition
- AI prediction using three deep learning models: LSTM, CNN-LSTM, and GRU
- Smart ensemble averaging of the best two model outputs
- 7-day temperature forecast trend visualization
- Interactive weather heatmap using Folium
- Error rate bar chart comparing model accuracy
- Dark mode toggle and frosted glass UI for enhanced experience

## Technologies Used

- Python
- Streamlit
- TensorFlow / Keras
- Plotly
- Folium
- OpenWeatherMap API
- SpeechRecognition & Pyttsx3

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-forecasting-app.git
   cd weather-forecasting-app
Create a virtual environment and install dependencies:
pip install -r requirements.txt

Add your OpenWeatherMap API key in the app.py file:
API_KEY = "your_api_key_here"

Run the Streamlit app:
streamlit run app.py
