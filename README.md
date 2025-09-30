# Customer-Churn-Prediction-with-Feature-Engineering

## Project Description

This project focuses on applying feature engineering techniques to improve the accuracy of customer churn prediction for a telecommunications company. The core idea is to demonstrate the value of creating new, more informative features from raw data to enhance machine learning model performance. We build and compare a baseline model using original features against models trained on engineered features. The project explores various feature creation methods, evaluates different classification models, and analyzes the impact of feature engineering on prediction metrics, particularly the F1-score for the churn class.

## Tech Stack

*   **Python:** The primary programming language for data manipulation, model building, and evaluation.
*   **pandas:** Used extensively for data loading, cleaning, feature engineering, and analysis.
*   **NumPy:** Used for numerical operations.
*   **Matplotlib:** Used for creating static visualizations, like feature importance plots.
*   **Seaborn:** Used for creating informative statistical graphics.
*   **scikit-learn:** Provides tools for data splitting, preprocessing (scaling, encoding), feature selection (SelectFromModel, RFE), model building (Logistic Regression, RandomForestClassifier, GradientBoostingClassifier, SVC), model evaluation (classification report, accuracy score), and hyperparameter tuning (GridSearchCV, RandomizedSearchCV).
*   **xgboost:** Used for the XGBoost classification model.
*   **lightgbm:** Used for the LightGBM classification model.
*   **Google Colab:** The environment where the notebook was developed and executed.
*   **Git:** Used to clone the dataset from a GitHub repository.

## How to Run

1.  **Open the notebook in Google Colab:** Upload or open the notebook file (`.ipynb`) in your Google Colab environment.
2.  **Install dependencies:** Ensure you have the necessary libraries installed. If running in a new Colab environment, the notebook includes `!pip install` commands for `xgboost` and `lightgbm`. For other libraries, you can install them using pip (refer to the `requirements.txt` file generated earlier).
3.  **Run all cells:** Execute all the code cells in the notebook sequentially from top to bottom. This will perform the data loading, cleaning, feature engineering, model training, evaluation, and analysis steps.

## Screenshots

**1. Visualization of Model Performance Comparision.**

<img width="700" height="402" alt="image" src="https://github.com/user-attachments/assets/7a229263-1833-4d0a-ae63-5a4180000290" />

**2. Statistics for Different Models Performance Comparision with Accuracy and F1-Score.**

<img width="428" height="265" alt="image" src="https://github.com/user-attachments/assets/7fbcdbce-b323-45fe-b579-646e91ea6618" />
