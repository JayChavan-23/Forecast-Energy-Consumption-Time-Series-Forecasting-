

# Forecast Energy Consumption: Time Series Forecasting ⚡️

This project focuses on analyzing and predicting energy consumption patterns using historical data. It involves comprehensive data preprocessing, feature engineering, exploratory data analysis (EDA), and the development of predictive models to forecast future energy usage.

## Project Overview

The primary goal is to identify seasonal patterns, daily fluctuations, and long-term consumption trends in household energy data. Using time-series forecasting, the project aims to provide practical insights for better energy management and resource allocation.

## Dataset Description

The analysis is performed on the `energydata_complete.csv` dataset, which contains 19,735 data points. Key variables include:

* **Target Variable**: `Appliances` (Energy use in Wh).
* **Temporal Data**: Date-time logs at 10-minute intervals.
* **Internal Metrics**: Temperature and humidity levels from various rooms (Kitchen, Living Room, Bedroom, etc.).
* **External Weather Data**: Temperature, humidity, wind speed, visibility, and dew point from the Chièvres weather station.

## Key Implementation Steps

### 1. Data Preprocessing

* **Cleaning**: Verified that the dataset contains no missing or duplicate values.
* **Feature Engineering**: Extracted time-based features such as month, weekday, hour, and day of the week to capture temporal trends.
* **Refinement**: Dropped non-contributory columns (e.g., the `lights` column, where 77% of values were zero) and renamed technical labels to human-readable room names (e.g., `T1` to `KITCHEN_TEMP`).

### 2. Exploratory Data Analysis (EDA)

* **Heatmap Analysis**: Utilized pivot tables and heatmaps to visualize mean daily energy consumption across different months.
* **Trend Identification**: Analyzed the relationship between internal environmental factors (temperature/humidity) and energy usage.

### 3. Time Series Forecasting

* Implementation of predictive models (as outlined in the assignment specification) to forecast energy demand based on historical patterns.

## Technical Stack

* **Language**: Python
* **Environment**: Jupyter Notebook (Datalore)
* **Libraries**:
* Data Manipulation: `Pandas`, `NumPy`
* Visualization: `Matplotlib`, `Seaborn`, `Plotly`
* Modeling: `Statsmodels` / `Scikit-learn`



## Repository Structure

* `a1936480_Jay Chavan_assign2 (1).ipynb`: Main project notebook containing all code and discussions.
* `energydata_complete.csv`: Raw dataset used for analysis.
* `a1936480_Jay Chavan_assign2 – Datalore.pdf`: Exported report of the analysis.
* `README.md`: Project documentation.

---

### Author

**Jay Chavan**
University of Adelaide | Student ID: a1936480
