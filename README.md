# Oilfield Location Optimization Project

**Objective:** Identify optimal locations for 200 new oil wells using machine learning to maximize profitability for OilyGiant.

## Overview
This project utilizes linear regression to analyze geological data and predict oil reserve volumes. Bootstrapping techniques assess potential benefits and risks to select the most profitable region for development.

## Key Steps:
1. **Data Preparation:** 
   - Analyze data from three regions (`geo_data_0.csv`, `geo_data_1.csv`, `geo_data_2.csv`).
   - Features include oil well identifiers and reserve-related characteristics.

2. **Model Training:** 
   - Apply linear regression to predict reserve volumes.
   - Evaluate predictions using RMSE and reserve averages.

3. **Profit Calculation:** 
   - Based on a $100M budget for 200 wells, calculate profitability per well and compare with reserve predictions.

4. **Risk Assessment:** 
   - Use bootstrapping (1000 samples) to evaluate risks and ensure loss probability < 2.5%.

## Outcomes:
- **Selected Region:** Recommend the region with the highest average profit and lowest risk, backed by robust data analysis.

## Tools:
- Python libraries: `Pandas`, `NumPy`, `scikit-learn`
- Techniques: Bootstrapping, Linear Regression
