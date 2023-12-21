# Predicting UK National Electricity Demand 

## Overview
This repository contains a web-app that can be used to support a real-world energy trading workflow. The app is backed by a comprehensive suite of tools and notebooks for processing, analyzing, predicting, and visualising this data. 

## Contents
1. `data_handling_main.ipynb` - Primary notebook for initial data processing and handling.
2. `data_handling_extended.ipynb` - Extended data handling procedures for complex scenarios.
3. `weather_data_pull.py` - Script to pull weather data from the OpenWeatherMap API.
4. `weather_data_process.py` - Script for processing the raw weather data.
5. `XGB_model.sav` - Pre-trained XGBoost model for demand prediction.
6. `SARIMAX.ipynb` - Notebook detailing the SARIMAX modeling approach.
7. `XGB.ipynb` - Notebook for XGBoost model implementation and evaluation.
8. `webapp.py` - Python script for a web application to display demand predictions.
9. `benchmarking_prophet_multi.ipynb` - Benchmarking notebook for multi-variate Prophet models.
10. `benchmarking_prophet_uni.ipynb` - Benchmarking notebook for uni-variate Prophet models.

## Installation
To set up this project, clone the repository and install the required dependencies:
```bash
git clone <repository-url>
cd <repository-name>
pip install -r requirements.txt
```

## Usage
Each notebook and script is self-contained with detailed comments explaining the functionality. Run Jupyter notebooks to understand the modeling process, and execute Python scripts for data processing and web application setup.
