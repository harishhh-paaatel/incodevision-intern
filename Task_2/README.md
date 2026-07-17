## Task 02 — Linear Regression Model

```markdown
# Task 02: Linear Regression Model — House Price Prediction

## Overview
A supervised machine learning project that builds a linear regression model to predict house prices based on features such as area, number of bedrooms, and location.

## Objectives
- Preprocess real-world housing data
- Train a linear regression model
- Evaluate model performance using standard regression metrics
- Visualize predicted vs. actual results

## Tech Stack
- **Python**
- **Pandas** & **NumPy** – data preprocessing
- **Scikit-learn** – model building and evaluation
- **Matplotlib** & **Seaborn** – result visualization

## Workflow
1. **Data Loading & Preprocessing**
   - Handle missing values
   - Encode categorical features
   - Split data into training and test sets
2. **Model Training**
   - Train a `LinearRegression` model using scikit-learn
3. **Evaluation**
   - Mean Squared Error (MSE)
   - R² Score
4. **Visualization**
   - Actual vs. Predicted price plots
5. **Optional Enhancements**
   - Feature scaling
   - Correlation analysis
   - Multiple regression for improved accuracy

## Key Learnings
Supervised learning fundamentals, model evaluation techniques, and predictive analytics using regression.

## How to Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
python task02_linear_regression.py