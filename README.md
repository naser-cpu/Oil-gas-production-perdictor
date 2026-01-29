# Oil & Gas Production Analysis

A machine learning project that analyzes historical oil and gas production data from 1932-2014 across 187 countries using the Kaggle Oil & Gas Production Dataset.

## Overview

This project performs exploratory data analysis and builds a Linear Regression model to predict oil production values based on features like production volume, oil prices, gas production, and population data.

## Key Features

- Comprehensive EDA with missing values analysis, distributions, and correlations
- Data visualization including production trends and top producing countries
- Linear Regression model for oil value prediction
- Model evaluation with RMSE, MAE, and R-squared metrics

## Requirements

- Python 3.12+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- ipykernel

## Installation

1. Clone the repository
2. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn ipykernel
   ```
3. Extract the dataset: `data/Oil and Gas 1932-2014.csv.zip`

## Virtual Environment Setup

It's recommended to use a virtual environment to isolate project dependencies and avoid conflicts with system packages.

```bash
python -m venv .venv
source .venv/bin/activate 
```

## Usage

Run the Jupyter notebook `oil_gas_production_analysis.ipynb` to see the complete analysis and model training process.

## Results

The Linear Regression model achieves an R-squared score of 0.747 on the test set, with oil production volume being the most important predictor of oil value.