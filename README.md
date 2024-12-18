## Python API Challenge
---
# VacationPy and WeatherPy Analysis

---

## Table of Contents
- [Description](#description)
- [Data Files](#data-files)
- [Features](#features)
- [Installation](#installation)
- [Results](#results)

---

## Description

The **VacationPy and WeatherPy Analysis** project utilizes **Python** and various APIs to analyze and visualize weather patterns across cities. It combines weather data, geospatial mapping, and key metrics to identify suitable vacation spots based on user preferences.

This project includes two key components:
1. **WeatherPy**: Focused on retrieving and analyzing weather data using OpenWeatherMap API.
2. **VacationPy**: Builds on WeatherPy results to locate vacation spots and create a visual travel itinerary using geospatial data.

---

## Data Files

| File Name                 | Description                                                   |
|---------------------------|---------------------------------------------------------------|
| `WeatherPy.ipynb`         | Jupyter Notebook for retrieving and analyzing weather data.   |
| `VacationPy.ipynb`        | Jupyter Notebook for identifying and mapping vacation spots.  |
| `api_keys.py`             | Python file storing API keys (e.g., OpenWeatherMap, Google).  |
| `.gitignore`              | .gitignore to hide the api_keys.py file from public viewing.  |
| `cities.csv`              | CSV file containing city data for analysis.                  |

---

## Features

1. **Weather Data Analysis (WeatherPy)**:
   - Fetches weather data for a list of cities using OpenWeatherMap API.
   - Analyzes temperature, humidity, cloudiness, and wind speed across cities.
   - Filters cities based on desired weather conditions.

2. **Vacation Spot Identification (VacationPy)**:
   - Uses filtered weather data to locate ideal vacation spots.
   - Incorporates Google Maps API to retrieve nearby hotels and plot them.

3. **Geospatial Visualizations**:
   - Creates maps using **gmaps** to display weather and vacation spots.
   - Visualizes hotel locations on a global scale.

4. **Integration of APIs**:
   - OpenWeatherMap API for weather data.
   - Google Maps API for geospatial mapping and hotel searches.

---

## Installation

1. **Prerequisites**:
   - Python 3.x
   - Jupyter Notebook or JupyterLab
   - User generated API keys for GeoApify and OpenWeather

2. **Setup**:
   - Clone this repository or download the project files.
   - Install dependencies using the provided `requirements.txt` file:
     ```bash
     pip install -r requirements.txt
     ```
   - Add your API keys in an `api_keys.py` file for:
     - OpenWeatherMap API
     - Google Maps API

3. **Run**:
   - Launch the Jupyter Notebooks:
     ```bash
     jupyter lab
     ```
   - Open and run `WeatherPy.ipynb` and `VacationPy.ipynb` sequentially.

---

## Results

### Key Insights:

1. **Weather Trends**:
   - Identified global patterns in temperature, humidity, cloud cover, and wind speed.
   - Verified the relationship between latitude and temperature.

2. **Vacation Spot Analysis**:
   - Located vacation spots based on ideal weather conditions.
   - Mapped hotels near selected vacation spots for easy visualization.

3. **Geospatial Mapping**:
   - Visualized global weather data and vacation spots using interactive maps.