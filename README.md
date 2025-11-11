# Fuel Price Time Series Forecasting

This repository contains the code and data for analyzing historical fuel price trends and forecasting future values using ARIMA and SARIMA models. Results are visualized in an interactive Streamlit web app.

## Overview

This project applies statistical time series modeling to weekly fuel price data, enabling users to generate forecasts and visualize trends. The workflow is implemented in Python, with deployment through Streamlit for usability and exploration.

## Repository Structure

- `README.md`  
  Project documentation and user instructions.
- `TSACode.ipynb`  
  Jupyter notebook containing the analysis and time series modeling code.
- `app.py`  
  Streamlit application for interactive visualization and forecasting.
- `dataset.txt`  
  Link to the external dataset used for analysis.
- `deployed.txt`  
  Link to the live Streamlit deployment (if available).
- `requirements.txt`  
  Dependency list for environment setup.
- `weekly_fuel_prices_all_data_from_...csv`  
  Main dataset for weekly fuel prices (2005–2022).

## Setup and Installation

To run the project on your local machine, follow these steps:

1. Clone the repository:
    ```
    git clone https://github.com/your-username/fuelprice-timeseries-forecasting.git
    cd fuelprice-timeseries-forecasting
    ```
2. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Run the Streamlit application:
    ```
    streamlit run app.py
    ```

## Usage

After starting the Streamlit application, navigate through the sidebar to select different fuel products, visualize historical data, and generate forecasts.
