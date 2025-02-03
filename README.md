# Week-2

# Solar Power Prediction Model
This project is designed to predict solar power generation (generated_power_kw) using linear regression. The model is trained on a dataset that includes various features related to solar power generation. The code applies necessary steps for preprocessing, model evaluation, and user input handling, offering a robust solution for solar power prediction.

# Features:
# 1. Data Preprocessing:
The dataset is loaded from a CSV file (solar power.csv), where the target variable is generated_power_kw, and the remaining columns are used as features.

# 2. Feature Scaling:
The features are standardized using StandardScaler to ensure that all input features have the same scale. This helps improve the model's performance and accuracy.

# 3. Model Training:
The model is trained using Linear Regression. The dataset is split into training (80%) and testing (20%) sets for training and evaluation.

# 4. Model Evaluation:
The model's performance is evaluated using Mean Squared Error (MSE) and R-squared (R²) metrics. These metrics help assess the accuracy of the predictions.

# 5. Model Persistence:
The trained model and feature scaler are saved using joblib to .pkl files. This allows for the reuse of the model and scaler without needing to retrain them, ensuring efficient future predictions.

# 6. Input Validation:
The script ensures that the user inputs valid numerical values when prompted for features. Invalid inputs trigger an error message, prompting the user to try again until valid data is provided.

# 7. Prediction:
After model training and evaluation, the user can input feature values, and the model will predict the solar power output (generated_power_kw) for the given inputs.

# Requirements:
Python 3.x
Libraries:
pandas
numpy
sklearn
joblib

