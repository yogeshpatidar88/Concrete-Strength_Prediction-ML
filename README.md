# Concrete Strength Prediction and Comparison of Different Linear Models

## Project Overview
This project predicts the compressive strength of concrete using linear regression models and compares their performance. Accurate predictions can help optimize material composition for safety and durability.

## Dataset
The dataset contains features like:
- Cement, Blast Furnace Slag, Fly Ash, Water
- Superplasticizer, Coarse Aggregate, Fine Aggregate
- Age (days)
- Concrete compressive strength (target)

Dataset source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength)

## Methodology
1. Data Preprocessing
   - Handle missing values
   - Scale features
   - Train-test split

2. Exploratory Data Analysis (EDA)
   - Visualize distributions
   - Correlation analysis

3. Modeling
   - Linear Regression
   - Ridge Regression
   - Lasso Regression
   - Elastic Net Regression

4. Evaluation Metrics
   - MSE, RMSE, R² Score

5. Comparison
   - Compare models using metrics
   - Select the best-performing model

## Usage
1. Clone repo:
   ```bash
   git clone https://github.com/yourusername/concrete-strength-prediction.git
   cd concrete-strength-prediction
