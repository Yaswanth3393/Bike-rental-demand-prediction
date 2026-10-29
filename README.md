# Bike Rental Demand: Analysis & Prediction (PRCP-1018)

Analysis of the Capital Bikeshare dataset (2011–2012) and prediction of daily
rental count from weather and seasonal features.

## Contents
- Task 1: Full data analysis report (EDA, statistical tests, insights)
- Task 2: Daily rental prediction (11 models, tuning, cross-validation)
- Model comparison report and production recommendation
- Report on challenges faced and techniques used

## Key results
- Best model: RBF-kernel SVR, test R² ≈ 0.91, RMSE ≈ 592 bikes/day
- Chronological (future) test: R² ≈ 0.74
- Linear models: R² ≈ 0.84
- Main demand drivers: temperature, season, weather, year-on-year growth

## How to run
pip install -r requirements.txt
jupyter notebook PRCP-1018-BikeRental-Analysis.ipynb
(Run All; the Data folder must be next to the notebook.)

## Dataset
UCI Bike Sharing Dataset (Fanaee-T & Gama). day.csv: 731 rows, hour.csv: 17,379 rows.
