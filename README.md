🏃‍♂️ Calorie Burn Prediction

This project predicts the number of calories burned during physical activity based on various factors such as gender, age, height, weight, duration, heart rate, and body temperature.
It uses Machine Learning regression model to train and predict calorie burn efficiently.

📚 Project Overview

The goal of this project is to create a model that accurately predicts calorie expenditure using health and activity data.
Such prediction can help in fitness tracking, personalized diet planning, and workout optimization.

🚀 Features

Data preprocessing and cleaning

Exploratory data analysis (EDA) with visualizations

Model training using regression algorithm

Model evaluation


🧠 Machine Learning Model Used

XGBoost Regressor

Evaluation using MAE

🗂️ Dataset

The dataset contains the following columns:

Column Name	Description
Gender	Male / Female
Age	Age of the person (years)
Height	Height (cm)
Weight	Weight (kg)
Duration	Duration of activity (minutes)
Heart Rate	Average heart rate during activity
Body Temperature	Body temperature during activity
Calories	Calories burned (target variable)

Dataset Source: : Kaggle - Calories Burnt Prediction Dataset

⚙️ Installation and Setup

You can run this notebook using Google Colab or your local Jupyter environment.

Steps:

Clone this repository

Open the notebook in Google Colab or Jupyter Notebook

Install dependencies (if running locally):

pip install pandas numpy scikit-learn matplotlib seaborn xgboost


Run all cells to train the model and view predictions.

📈 Results

Achieved high accuracy in predicting calorie burn using the trained model.

XGBoost performed better than Linear Regression in most cases.

Visualization of feature importance and correlations provided key insights into which variables most affect calorie burn.

🧩 Technologies Used
Category	Tools / Libraries
Language	Python
Environment	Google Colab
Libraries	Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
📊 Example Prediction
Input	Predicted Calories
Male, 25 years, 175 cm, 70 kg, 30 mins, 110 bpm, 98.5°F	220.4 kcal



👤 Author

Divya Prakash 

📧 [raydivyaprakash@gmail.com]

💻 [My GitHub Profile](https://github.com/divyaPrakash2004)
