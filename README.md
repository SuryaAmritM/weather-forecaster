[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SuryaAmritM/weather-forecaster/blob/main/Advanced_Weather_Predictor.ipynb)

# Advanced Weather Predictor

This project uses machine learning to predict the average temperature for the next 7 days based on historical weather data of Indian cities. It also compares predictions with real-time weather data using OpenWeatherMap API.

## Features
- Forecasts next 7 days temperature for any Indian city in the dataset
- Compares with real-time temperature using OpenWeatherMap API
- User input for city name
- Visualization and table of results
- Built using: pandas, scikit-learn, matplotlib, tabulate

## How to Use
1. Upload city-wise weather CSVs in the `data/` folder
2. Set your OpenWeatherMap API key
3. Run the notebook
4. Enter the city name to get the forecast

## Requirements
- Python 3.8+
- pandas
- scikit-learn
- requests
- matplotlib
- tabulate

## Example
🌤️  7-Day Weather Forecast:

│ Day   │ Date                   │ Predicted Avg Temp   │

│ Day 1 │ Tuesday, 29 Jul 2025   │ 30.50 °C             │
│ Day 2 │ Wednesday, 30 Jul 2025 │ 30.18 °C             │
│ Day 3 │ Thursday, 31 Jul 2025  │ 30.08 °C             │
│ Day 4 │ Friday, 01 Aug 2025    │ 29.86 °C             │
│ Day 5 │ Saturday, 02 Aug 2025  │ 29.92 °C             │
│ Day 6 │ Sunday, 03 Aug 2025    │ 29.85 °C             │
│ Day 7 │ Monday, 04 Aug 2025    │ 29.37 °C             │


Built by Surya Amrit
