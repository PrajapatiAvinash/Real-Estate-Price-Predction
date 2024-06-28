# Real Estate Price Prediction

## Overview

This project aims to predict real estate prices using machine learning techniques. The dataset used is from Bangalore's real estate market. The project involves data cleaning, outlier removal, encoding, model selection, and prediction using the Decision Tree Regressor.

## Dataset

The dataset used in this project contains real estate information from Bangalore. It includes various features such as location, size, price, number of bathrooms, and more.

## Data Preprocessing

1. **Data Cleaning**: Performed various tasks to clean the data and make it meaningful.
2. **Outlier Removal**: Removed outliers using normalization techniques to ensure the data is consistent and reliable.
3. **Encoding**: Used OneHotEncoder to encode categorical data.

## Model Selection

To determine the best algorithm for our dataset, cross-validation was employed. The Decision Tree Regressor was found to be the most effective model for our data.

## Implementation

1. **Data Splitting**: Split the dataset into training and testing sets.
2. **Model Training**: Trained the model using the training data.
3. **Prediction**: Developed a model that takes inputs in the form of the dataset and provides the predicted price.

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/real-estate-price-prediction.git
