# 🔮 Churn Prediction

This project involves predicting customer churn based on historical data to help businesses understand and predict which customers are likely to leave their service. It uses **Machine Learning** and **Flask** to deploy a predictive model for customer retention.

## 🛠️ Project Overview

The objective of this project is to build a **churn prediction model** using historical customer data. The model is trained using a **Random Forest Classifier** and deployed as a **Flask web application**. It takes input from a user through a web form and predicts whether a customer is likely to churn (leave the service) based on various features like contract type, monthly charges, customer tenure, and service usage.

### The application allows the following:

- **Predict churn likelihood**: Based on input data like customer tenure, service usage, etc.
- **Confidence Score**: The application provides a confidence score with the prediction.
- **User Input**: Users can input data about a customer through a simple web form, and the app will make predictions.

## 🔧 Tools and Libraries Used

- **Machine Learning**:
  - `scikit-learn`: Used for training the predictive model (Random Forest Classifier).
  - `pandas`: Data manipulation and preprocessing.
  - `pickle`: For saving and loading the trained model.
  
- **Web Framework**:
  - `Flask`: A lightweight web framework to deploy the machine learning model and interact with the user through a web interface.


## 🚀 How It Works

1. **Data Input**: The user inputs the customer’s data through a web form (e.g., monthly charges, tenure, contract type, etc.).
2. **Data Preprocessing**: The input data is processed and transformed into a suitable format using **pandas** (e.g., one-hot encoding for categorical variables).
3. **Model Prediction**: The preprocessed data is passed into a trained **Random Forest** model to predict the likelihood of the customer churning.
4. **Result Display**: The application displays whether the customer is likely to churn and the confidence score of the prediction.

## 📝 Features

- **User Form Input**: The user inputs customer data (e.g., tenure, monthly charges, contract type).
- **Churn Prediction**: The model predicts if the customer is likely to churn.
- **Confidence Score**: The prediction comes with a confidence score indicating how certain the model is about the prediction.
- **Web Interface**: Simple web interface built using Flask for easy user interaction.
