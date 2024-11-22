ECE School Project
# **PredictHouse: Analysis and Prediction of the Californian Housing Market**

## 📚 Project Overview
**PredictHouse** is a machine learning project aimed at analyzing and predicting housing prices in California. By leveraging data from Scikit-learn's California Housing dataset, this project demonstrates the application of machine learning methods for regression and classification tasks. 

The project also explores statistical analysis, model optimization, and visualization techniques to deliver meaningful insights into the dataset.

---

## 🧑‍🎓 Purpose
This project is part of a school assignment designed to:
- Explore and analyze a structured dataset.
- Build and compare machine learning models for prediction.
- Visualize prediction results to communicate insights.
- Understand the mathematical and theoretical foundations of the models used.

---

## 🚀 Features
1. **Data Analysis**:
   - Statistical exploration of features.
   - Identification of missing values, outliers, and correlations.
   - Domain analysis of the housing market.

2. **Regression Models**:
   - Predict the median house value using multiple regression algorithms.
   - Evaluate model performance with metrics such as MAE, RMSE, and R².

3. **Classification Models**:
   - Categorize house prices into "Low," "Medium," and "High" using machine learning classifiers.
   - Validate results with confusion matrices and accuracy scores.

4. **Visualization**:
   - Scatter plots and heatmaps for data relationships.
   - Graphical comparison of true vs. predicted values.

5. **Theoretical Formalism**:
   - Provide mathematical explanations for the best-performing models.
   - Analyze the impact of hyperparameters on model performance.

---

## 📁 Project Structure
```
predict-house/
│
├── data/
│   └── cleaned_california_housing.csv   # Cleaned dataset
│
├── results/
│   ├── regression/
│   │   ├── regression_metrics.csv       # Regression metrics
│   │   └── regression_predictions.csv   # Regression predictions
│   │
│   ├── classification/
│   │   ├── classification_metrics.csv   # Classification metrics
│   │   └── classification_predictions.csv  # Classification predictions
│   │
│   └── feature_importances/
│       └── rf_feature_importances.csv   # Random Forest feature importances
│
└── notebooks/
    ├── 1_data_analysis.ipynb            # EDA notebook
    ├── 2_regression_model.ipynb         # Regression notebook
    ├── 3_classification_model.ipynb     # Classification notebook
    ├── 4_visualisation.ipynb            # Visualization notebook
    └── 5_theory_formalism.ipynb         # Theoretical background notebook

```