# 🧑‍🦼Food Delivery Time Prediction

## 🔑Introduction

Online food delivery services have become very popular today. Customers want their food delivered quickly and with accurate time estimates. However, many food delivery companies find it hard to give precise delivery times because of unpredictable factors like traffic, weather, and how long restaurants take to prepare food.

Most food delivery platforms now use basic methods such as historical averages to guess delivery times. These methods don’t account for real-time changes and often give wrong predictions. This causes unhappy customers and makes delivery less efficient.

The main goal of this project is to build a predictive model using Python that can estimate food delivery times more accurately. The model will analyze historical delivery data and important factors such as delivery distance, the delivery person’s experience, and their ratings. This will help improve delivery planning and customer satisfaction.

---

## ⚒Objectives

The primary objectives of this project are:

- **To design a model** that can accurately predict food delivery time.  
- **To reduce customer waiting times** by providing accurate delivery time estimates.  
- **To analyze the impact** of delivery time predictions on customer satisfaction.  
- **To create a simple platform** where both restaurants and customers can check estimated delivery times easily.  
- **To use historical delivery data** to improve prediction accuracy over time.

Predicting food delivery times with machine learning can help improve customer satisfaction and overall delivery service efficiency. By analyzing past data and using predictive models, food delivery companies can provide more accurate delivery time estimates. This leads to happier customers, and using real-time data will make predictions even more reliable.


## 🎯Model Performance Metrics

The performance of each model was evaluated using **Mean Squared Error (MSE)**, **R-squared (R²)**, and **Mean Absolute Error (MAE)** on the validation dataset.

| Model                | MSE    | R²    | MAE  |
|----------------------|--------|-------|------|
| **Random Forest**     | 66.55  | 0.24  | 6.33 |
| **Linear Regression** | 71.77  | 0.18  | 6.63 |
| **Decision Tree**     | 105.58 | -0.20 | 7.92 |
| **KNN (k=5)**         | 72.78  | 0.17  | 6.69 |

**Table 1: Model Performance Metrics**

*Here, we have assumed `random_state = 42` and number of neighbors `k = 5` for KNN.*
