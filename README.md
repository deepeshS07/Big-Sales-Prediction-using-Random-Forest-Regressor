# Big Sales Prediction

## Project Overview

The **Big Sales Prediction** project aims to predict the sales of various items across different outlets using a **Random Forest Regressor** model. The goal is to help businesses forecast sales, improve inventory management, and develop better pricing strategies. The project uses the **Big Sales Data** dataset, which contains information about items, their sales, and outlet characteristics.

## Objective

The objective of this project is to predict **Item_Outlet_Sales** based on various features such as **Item_Identifier**, **Item_Weight**, **Item_Fat_Content**, **Item_Visibility**, **Item_Type**, and **Outlet_Identifier**. The model is built using the **Random Forest Regressor** algorithm, and the project emphasizes data preprocessing, feature engineering, and model evaluation.

## Dataset

The dataset, **Big Sales Data**, is downloaded from the **YBI Foundation GitHub Repository**. It contains 14,200 rows and several columns, including:

- **Item_Identifier**: Unique identifier for each item.
- **Item_Weight**: Weight of the item.
- **Item_Fat_Content**: Fat content (Low Fat or Regular).
- **Item_Visibility**: Visibility of the item in the store.
- **Item_Type**: Category of the item (e.g., Fruits, Household, Dairy).
- **Item_MRP**: Maximum Retail Price.
- **Outlet_Identifier**: Unique identifier for the outlet.
- **Outlet_Establishment_Year**: Year the outlet was established.
- **Outlet_Size**: Size of the outlet (Small, Medium, High).
- **Outlet_Location_Type**: Location type (Tier 1, Tier 2, Tier 3).
- **Outlet_Type**: Type of outlet (e.g., Supermarket, Grocery Store).
- **Item_Outlet_Sales**: Target variable representing the sales of the item in the outlet.

## Steps and Methodology

1. **Import Libraries**: The necessary libraries for data manipulation, visualization, and modeling were imported.
2. **Import Data**: The dataset was loaded into a DataFrame for easier manipulation.
3. **Describe Data**: Basic summary statistics of the dataset were examined to understand the structure, distribution of values, and missing data.
4. **Data Visualization**: Visualizations were created to explore relationships between features and identify patterns, outliers, or correlations.
5. **Data Preprocessing**: The dataset underwent various preprocessing steps, including handling missing values, encoding categorical variables, and transforming features for model training.
6. **Define Target Variable (y) and Feature Variables (X)**: The target variable, **Item_Outlet_Sales**, was separated from the feature variables.
7. **Train-Test Split**: The data was split into training and testing sets to evaluate model performance.
8. **Modeling**: The **Random Forest Regressor** model was trained using the training data.
9. **Model Evaluation**: After training the model, performance metrics such as **Mean Absolute Error (MAE)** and **R² score** were calculated to evaluate model accuracy and performance.
10. **Prediction**: The trained model was used to make predictions on the test set, and the predicted sales were compared to actual sales values.

## Conclusion

This project demonstrates how to use the **Random Forest Regressor** model to predict item sales in retail outlets. The model, through its feature selection and training, provides useful insights into the sales behavior of items across outlets. Further improvements can be made by optimizing the model with hyperparameter tuning or experimenting with more advanced algorithms.

## Future Work

- Experimenting with advanced models such as **XGBoost** and **Gradient Boosting** to improve accuracy.
- Fine-tuning the **Random Forest Regressor** using hyperparameter optimization methods such as **Grid Search** and **Randomized Search**.
- Further data preprocessing to handle outliers and refine feature engineering.

