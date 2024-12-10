# Car_Price_Prediction
This project focuses on predicting car prices using Machine learning techniques like Linear Regression

---

## Project Overview

The "Car Price Prediction" project aims to develop a model that accurately predicts car prices based on various features, such as the current price, fuel type, transmission type etc. This prediction task is essential in the automotive industry, aiding buyers, sellers, and dealers in making informed decisions. By employing machine learning algorithms and a curated Kaggle dataset, this project provides a powerful tool for estimating car prices.

---

## Key Features

### **Data Collection and Processing**:
The project uses a dataset sourced from [Kaggle](https://www.kaggle.com). This dataset contains features like the year of manufacture, kilometers driven, fuel type, transmission type, current price etc. Using Pandas, the data is cleaned, processed, and transformed to ensure it is ready for analysis.

### **Data Visualization**:
The project employs data visualization techniques to explore the dataset and gain insights. Using Matplotlib and Seaborn, visualizations such as scatter plots and heatmaps are created to analyze trends, patterns, and relationships between features.

### **Correlation Analysis**:
A heatmap is used to display the correlation between features and the target variable (selling price).

### **Train-Test Split**:
To evaluate the performance of the regression model, the project employs a train-test split. The dataset is divided into training and testing subsets, ensuring the model is trained on a portion of the data and evaluated on unseen data for an accurate assessment of its predictive capabilities.

### **Regression Model using Linear Regression**:
The project utilizes Linear Regression from Scikit-learn to predict car prices. Linear Regression is a simple yet effective algorithm for modeling the relationship between input features and the target variable.

### **Model Evaluation**:
The project evaluates the model's performance using metrics such as **Mean Absolute Error (MAE)** and **R-squared Score**. These metrics provide insights into the accuracy and reliability of the model. Additionally, scatter plots are used to compare the predicted prices with actual prices.

---

## Getting Started

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
    gh repo clone Rikitha1007/Car_Price_Prediction
2. **Install the required libraries**: If you're using Google Colab, you don't need to install any libraries manually. Simply import the dependencies as shown in the notebook.
3. **Launch Google colab**:
   ```bash
   https://colab.research.google.com/
4.**Open the Notebook**: Upload and open the car_price.ipynb file in Google Colab or Jupyter Notebook, and run the cells sequentially.

