# Accident Risk Prediction & Analysis

## Overview
This project analyzes large-scale accident datasets to identify key risk factors and build predictive regression models using machine learning techniques.

The analysis focuses on uncovering accident severity patterns, evaluating contributing variables, and comparing model performance using statistical evaluation metrics.

---

## Objectives
- Analyze accident-related trends and contributing variables
- Perform exploratory data analysis and preprocessing
- Build predictive regression models using machine learning
- Evaluate model performance using statistical metrics and cross-validation

---

## Dataset Information
- Train Dataset: 517,754 rows × 21 columns
- Test Dataset: 172,585 rows × 21 columns
- Source: Kaggle Accident Dataset

Dataset Link:
[https://www.kaggle.com/](https://www.kaggle.com/)

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Methodology
1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis
3. Feature Selection & Correlation Analysis
4. Regression Model Development
5. Model Evaluation using RMSE, MAE, and R²
6. Cross-Validation Analysis

---

## Model Performance

### Random Forest Regressor
- RMSE: 0.0574
- MAE: 0.0444

### Linear Regression
- RMSE: 0.0735
- MAE: 0.0583

### Evaluation Metrics
- R² Score: 0.8806
- Average Cross-Validation R²: 0.8817

---

## Key Insights
- Random Forest significantly outperformed Linear Regression in predictive consistency
- Cross-validation scores demonstrated stable model generalization across datasets
- Multiple environmental and operational variables showed strong influence on accident severity patterns
- Large-scale preprocessing and feature analysis workflows improved model performance evaluation

---

## Repository Structure

```text
├── data/
├── notebook/
├── images/
├── README.md
├── requirements.txt
```

---

## Future Improvements
- Hyperparameter tuning for model optimization
- Additional feature engineering workflows
- Interactive dashboard integration
- Real-time prediction deployment using Streamlit
