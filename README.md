# Traffic Analysis and Route Optimization

## Overview
This project is a **Traffic Analysis and Route Optimization** tool built using **Streamlit**. It fetches real-time traffic data, analyzes different routes, and displays the fastest route along with estimated travel time, distance, and fuel cost. Additionally, it provides a visual map representation and traffic trend analysis.

## Features
- 📍 **Fetches real-time traffic data** using Google Maps API.
- 🚦 **Displays traffic trends** to help users choose the best travel time.
- 🗺 **Interactive map visualization** with Folium.
- 🛣 **Identifies the fastest route** based on real-time data.
- ⏳ **ETA calculation and display** in a user-friendly format.
- 💰 **Fuel cost estimation** based on distance and fuel efficiency.

## Installation
### Prerequisites
Ensure you have **Python 3.8+** installed.

### Install Required Packages
Run the following command to install all dependencies:
```sh
pip install -r requirements.txt
```

### Required API Key
You need a **Google Maps API Key** to fetch real-time traffic data. Add your API key in your project’s environment variables or within the code.

## Usage
1. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
2. Run the application:
   ```sh
   streamlit run app.py
   ```

## Technologies Used
- **Python** - Core language
- **Streamlit** - Web framework
- **Google Maps API** - Traffic and route data
- **Folium** - Map visualization
- **Plotly** - Data visualization
- **Pandas** - Data processing

## Folder Structure
```
minor/
│-- app.py
│-- requirements.txt
│-- traffic_analysis.py
│-- map_display.py
```

## Contributing
Feel free to contribute by opening issues or submitting pull requests.

