# Bangalore House Price Prediction

This project implements a Bangalore house price prediction system using Linear Regression. It is built as an end-to-end machine-learning project using Flask.

## Overview

The goal of this project is to predict the price of houses based on various features such as location, total square feet area, number of bathrooms, and number of bedrooms.

## Features

- **Effective Model Selection:** The best-performing model for house price prediction was selected, with Linear Regression demonstrating strong generalization.
- **Accurate Predictions:** The model provided high accuracy, with a solid R² score on the test set, ensuring reliable predictions of house prices.
- **Streamlined Data Pipeline & Deployment:** A comprehensive data pipeline was built, integrating preprocessing and feature encoding. The model was serialized and deployed for real-time predictions, reducing retraining time.
- **Scalable & User-Friendly Web Interface:** A Flask web app was developed with an intuitive interface, supporting real-time predictions and scalability for future enhancements.

## Project Structure

The project is structured as follows:

- `app.py`: Flask web application for serving predictions.
- `model/`: Directory containing trained model and preprocessing objects.
- `dataset/`: Directory containing the dataset used for training.
- `templates/`: HTML templates for the web interface.


---

## 🏆 Model Selection Process

Several machine learning models were trained and evaluated using **5-Fold Cross-Validation**. The **Ridge Regression model** achieved the best performance.

| **Model**                     | **Mean Cross-Validation R² Score** |
|--------------------------------|------------------------------------|
| **Linear Regression**          | **0.8035** |
| **Decision Tree Regressor**     | 0.6526 |
| **Random Forest Regressor**     | 0.7607 |
| **XGBoost Regressor**          | 0.7144 |

✅ **Best Selected Model:** **Linear Regression**  
✅ **Final Test R² Score:** **0.8035** 

**For Linear Regression model:**
Mean Absolute Error (MAE): 20.7057
Mean Squared Error (MSE): 1341.7307
Root Mean Squared Error (RMSE): 36.6296
Mean Absolute Percentage Error (MAPE): 24.0562%
Explained Variance Score: 0.8182
Adjusted R²: 0.8173

---

## Technologies Used

- Python
- Flask
- HTML/CSS
- Bootstrap
- scikit-learn

## Tools/APIs/Librarries used

Pandas, numpy, scikit-learn, xgboost, joblib, Werkzeug, itsdangerous, Jinja2, MarkupSafe, click, colorama, python-dateutil, pytz, threadpoolctl, tzdata, babel, pickle-mixin, Flask, HTML, CSS.