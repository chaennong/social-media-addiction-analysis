# Impact of User Metrics on Social Media Addiction

# Project Overview
This project investigates the relationship between user-specific variables—ranging from demographics to behavioral habits—and levels of social media addiction. Using a synthetic dataset designed to mimic real-world usage trends, we conducted an Exploratory Data Analysis (EDA) and built predictive models to identify the most significant drivers of addiction.

# Key Objectives

- **Exploratory Data Analysis**: Uncover patterns between user characteristics (age, platform preference, location) and addiction levels.
- **Predictive Modeling**: Compare the effectiveness of **XGBoost** and **Multinomial Logistic Regression** in classifying addiction severity.
- **Feature Importance**: Identify which behavioral metrics (e.g. productivity loss, self-control) serve as the strongest predictors.

# Methodology & Tools

- **Language**: Python
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`
- **Models**: XGBoost(Utilized for its ability to handle complex, non-linear relationships), Multinomial Logistic Regression(Used as a baseline for interpretability and linear relationship testing)

# Principal Findings

- **Model Performance**: The XGBoost model significantly outperformed Logistic Regression, achieving high accuracy in predicting addiction levels.
- **Key Predictors**: Behavioral attributes like **Productivity Loss** and **Self Control** were identified as the most impactful factors, while demographic factors like rural vs. urban settings showed less variation.

# How to Run

1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the `sns-analysis.ipynb` notebook.
