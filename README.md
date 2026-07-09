# CO₂ Emission Predictor

A machine learning project that predicts **CO₂ emissions from cars** using **Linear Regression**. Built with Python as part of a CS106 ML project.

## Dataset

The model uses `CO2_Emissions.csv` containing car specifications and their CO₂ output.

## Features Used

- **Engine Size (L)**
- **Cylinders**
- **Fuel Consumption Comb (L/100 km)**
- **Fuel Type** (label encoded)
- **Transmission** (label encoded)

**Target:** CO₂ Emissions (g/km)

## Workflow

1. **Data Preprocessing** — handle nulls, encode categorical variables
2. **Data Visualization** — pair plots, boxplots, and bar charts for feature analysis
3. **Modeling** — Linear Regression via scikit-learn (`train_test_split`, `LinearRegression`)
4. **Evaluation** — Mean Squared Error & R² score
5. **Prediction** — actual vs predicted scatter plot

## Results

The model outputs:
- **R² Score** — how well the model explains variance
- **Mean Squared Error** — prediction accuracy
- Feature weights and intercept for interpretability