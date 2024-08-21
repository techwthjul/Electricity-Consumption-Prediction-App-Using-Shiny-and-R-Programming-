# Electricity Consumption Prediction App

# Project Overview:
This project was developed as part of the course IST-687: Introduction to Data Science at Syracuse University. The primary goal of this application is to predict electricity consumption based on various input parameters such as square footage, number of bedrooms, heating setpoint, and environmental factors like temperature, humidity, and wind speed.

# Features:
Interactive UI: Users can input specific details about a property and environmental conditions to predict energy usage.
Prediction Model: The app utilizes statistical techniques to analyze and predict electricity consumption, providing an intuitive understanding of the factors influencing energy usage.
Visualization: The app includes a pie chart that visually represents the relative contribution of each input parameter to the energy usage prediction.
How the Project Was Built
1. Data Collection & Preprocessing:
Data Sources: We gathered historical data on electricity consumption, weather conditions, and building characteristics.
Data Cleaning: The data was cleaned and processed to handle missing values, normalize inputs, and ensure the dataset was ready for modeling.
2. Model Development:
Feature Engineering: We identified key features such as square footage, number of bedrooms, heating setpoint, dry bulb temperature, relative humidity, wind speed, and global horizontal radiation.
Model Selection: Various machine learning models were tested, including linear regression and decision trees, to identify the best fit for predicting energy consumption.
Model Evaluation: The selected model was evaluated using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to ensure accurate predictions.
3. App Development:
Backend: The backend of the app was developed using Python, with the model serving predictions based on user inputs.
Frontend: The frontend was designed using a web framework to provide a user-friendly interface for input and visualization.
Deployment: The app was deployed on a cloud platform, making it accessible to users for real-time energy usage predictions.
Usage
Input Data: Users can enter the date range, county, square footage, number of bedrooms, heating setpoint, dry bulb temperature, relative humidity, wind speed, and global horizontal radiation.
Predict: Click the "Predict Energy Usage" button to get the predicted energy usage.
Visualization: The app will display a pie chart showing the relative contribution of each input parameter to the prediction.
Project Link
You can access the app here: https://rijulugawekar17.shinyapps.io/IDSFINAL/

#Contributions:
Rijul Ugawekar: Developed the app as part of the IST-687 course, focusing on model development and app implementation.
#License:
This project is licensed under the MIT License.
