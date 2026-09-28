# Solar Power Generation Analysis & Prediction

## Goal
Analyse solar plant generation data alongside weather sensor data and predict DC power output.

## Dataset
Solar Power Generation Data (Kaggle), Plant 1: generation data and weather sensor data.

## Tools
Python, Pandas, Matplotlib, Seaborn, Scikit-learn, Google Colab

## Approach
1. Cleaned and merged generation and weather data on timestamp
2. Aggregated output across all inverters
3. Explored patterns with charts (hourly generation, irradiation vs power, correlations)
4. Trained Linear Regression and Random Forest models

## Results
- Linear Regression: R² = 0.994
- Random Forest: R² = 0.995

## Key Findings
- Power generation peaks around midday
- Irradiation has the strongest relationship with power output
- Linear Regression performs almost as well as Random Forest, confirming the near-linear relationship between irradiation and power
