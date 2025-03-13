# 🚀 Delivery Time Estimation Project

## 📌 Project Overview
This project aims to predict the delivery time of an order based on various factors such as distance, weather, traffic conditions, and courier experience. A linear regression model is used for estimation after preprocessing the dataset.

## 📊 Dataset Details
The dataset consists of the following features:
- **Order_ID**: Unique identifier for each order
- **Distance_km**: Distance to be traveled (in km)
- **Weather**: Weather conditions during delivery
- **Traffic_Level**: Traffic congestion level
- **Time_of_Day**: Time period during which the delivery occurs
- **Vehicle_Type**: Type of vehicle used for delivery
- **Preparation_Time_min**: Time taken to prepare the order (in minutes)
- **Courier_Experience_yrs**: Years of experience of the delivery person
- **Delivery_Time_min**: Actual delivery time (in minutes, target variable)

## Data Preprocessing
- Categorical variables are encoded using **get_dummies**.

## Model Used
- **Linear Regression** model is implemented for prediction.
- Achieved **83%** accuracy on the dataset.

## Usage
Run the script to preprocess the data and train the model for estimating delivery time based on input features.

---
<!-- **👩‍💻 Author:** Nandana Anil -->

