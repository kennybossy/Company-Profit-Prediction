# Profit Prediction for 50 startups

## Project Overview
This project aims to predict the profit of 50 startup companies based on multiple features such as **R&D Spend**, **Administration Spend**, **Marketing Spend**, and **State**. Using a multiple linear regression model, we can estimate how these factors contribute to the profitability of the startups. 

The dataset consists of 50 entries, and each entry includes details about the company's expenditures and the state in which the company operates. The project demonstrates how to use multiple linear regression to predict continuous output (profit).

## Key Features
- **Multiple Linear Regression Model**: The project uses a linear regression model to predict profits based on multiple input variables.
- **One-Hot Encoding**: The "State" categorical variable is transformed using one-hot encoding to be used in the regression model.
- **Train-Test Split**: The dataset is split into training and test sets to evaluate the model's performance.
- **Model Evaluation**: Metrics like R² score and Mean Absolute Error (MAE) are used to evaluate the model.
- **Data Visualization**: Key insights from the data are visualized using plots.

## Dataset
The dataset contains information about 50 startups, including the following features:
- **R&D Spend**: Amount spent on research and development.
- **Administration Spend**: Amount spent on administration.
- **Marketing Spend**: Amount spent on marketing.
- **State**: The state where the company is based (categorical variable).
- **Profit**: The profit made by the startup (target variable).


## Model Architecture
- **Multiple Linear Regression**: A statistical technique used to predict a dependent variable (Profit) based on multiple independent variables (R&D, Administration, Marketing Spend, and State).
- The project applies **Ordinary Least Squares (OLS)** method for model training.

## Technologies Used
- **Python 3**
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib** and **Seaborn**: For data visualization.
- **scikit-learn**: For implementing the linear regression model and data preprocessing (one-hot encoding, train-test split).
