# Assessing and Prediction of Flood

## Project Overview
The "Assessing and Prediction of Flood" project aims to predict flood risks based on environmental and geographical factors such as precipitation, river levels, and soil moisture. The project also includes post-flood recovery assessment based on recovery funds, infrastructure damage, and population affected.

## Features
- **Flood Prediction**: Predicts the likelihood of a flood occurring in different regions using a Random Forest model.
- **Geolocation**: Geocodes addresses to obtain latitude and longitude for accurate prediction.
- **Post-Flood Recovery Assessment**: Evaluates recovery speed based on various recovery-related features.
- **Visualization**: Generates a correlation heatmap to analyze feature relationships with flood occurrence.

## Installation
1. Clone the repository: git clone https://github.com/your-username/assessing-and-prediction-of-flood.git 
2. Install the required dependencies: pip install -r requirements.txt
3. Download or provide your own dataset (`dummy_flood_dataset.csv`).

## Usage
1. Prepare your dataset (`dummy-flood-dataset.csv`) with relevant columns like `address`, `precipitation`, `river_level`, `soil_moisture`, etc.
2. Open the Jupyter notebook:: jupyter notebook code.ipynb
3. The script will preprocess the data, train the Random Forest model, make predictions, and assess recovery speed. It will also display a correlation heatmap.

## Requirements
- pandas
- scikit-learn
- geopy
- matplotlib
- seaborn





