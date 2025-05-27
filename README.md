# Medical Cost Prediction with Linear Regression

This project uses the **Medical Cost Personal Dataset** from Kaggle to predict insurance charges based on patient data.

## Dataset Features

- `age`: Age of primary beneficiary
- `sex`: Gender (male/female)
- `bmi`: Body mass index
- `children`: Number of dependents
- `smoker`: Smoking status
- `region`: Region of residence
- `charges`: Medical insurance cost (target)

## ML Objective

- Type: **Supervised regression**
- Model used: **Linear Regression (from scikit-learn)**

## What you'll find in this project

- Data analysis and visualization (Seaborn, Matplotlib)
- One-hot encoding of categorical variables
- Model training and evaluation (MSE, R²)
- Model saving with `joblib`

## Files

- `insurance.csv` → Input dataset
- `regression_insurance.ipynb` → Jupyter Notebook
- `linear_regression_model.pkl` → Saved model
- `.gitignore` → Files to ignore from Git
