# Sales Forecasting Model README

## Overview

This project focuses on developing a sales forecasting model using historical sales data for 45 retail stores across different regions. The objective is to predict department-wide sales for each store, considering various factors such as promotional markdown events and macroeconomic indicators.

# Data Description
**stores.csv:** Contains anonymized information about the 45 stores, including store type and size.

**features.csv:** Provides details on markdown events and macroeconomic factors.

**train.csv:** Historical training data containing store, department, date, weekly sales, and holiday information.

## Key Steps

Data Preprocessing: Clean and prepare the data for analysis, including handling missing values and encoding categorical variables.

## Feature Engineering: 

Extract relevant features from the data, such as date-related features and store type.

## Model Training: 

Train a regression model (e.g., Linear Regression) using the prepared data.

## Model Evaluation:
Evaluate the trained model's performance using metrics like Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).

## Analysis and Insights: 

Analyze correlations, trends, and patterns in the data to gain insights into sales drivers and factors influencing sales performance.

## Files Included
**stores.csv**

**features.csv**

**train.csv**

**Jupyter Notebook (sales_forecasting_model.ipynb):** 
1. **Contains the Python code for data preprocessing**
2. **model training**
3. **evaluation**
4. **analysis**
5. **Trained Model File (linear_regression_model.joblib):** 
Serialized model file saved after training.

# Dependencies

```pandas
NumPy
scikit-learn
matplotlib
seaborn
joblib
```

# Usage
**Clone the repository:**https://github.com/Sarangandhi/Sales-Forecasting---regression-Model.git

Run the Jupyter Notebook sales_forecasting_model.ipynb to execute the code and reproduce the analysis.

View the model evaluation results, analysis, and insights generated from the notebook.


**License:** 

This project is licensed under the MIT License. See the LICENSE file for details.

**Contact** 

For any inquiries or feedback, please contact:

**Email:** sarangandhi66@gmail.com

**LinkedIn:** https://www.linkedin.com/in/saranraj-gandhi/

For any further questions, feel free to reach out.

# Author
Saranraj Gandhi
