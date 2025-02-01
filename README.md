# Ecommerce Customers Analysis

## 📜 Introduction

This project performs an **Exploratory Data Analysis (EDA)** and builds a **Linear Regression model** to analyze and predict customer behavior in an e-commerce platform. The goal is to explore key features of the dataset, identify customer segments, and derive insights to improve customer experience and drive sales.

## 🛍️ Dataset Overview

The dataset used in this project contains information about e-commerce customers, including:

- **CustomerID**: Unique identifier for each customer.
- **Age**: Customer's age.
- **Gender**: Customer's gender.
- **AnnualSpend**: Amount spent by the customer annually.
- **ProductsPurchased**: Number of products purchased.
- **LastPurchaseDate**: Date of the customer's last purchase.
- (Include any additional relevant columns based on your dataset.)

## 🗂️ Files in this Repository

- **`Ecommerce_Customers_Analysis.ipynb`**: Jupyter Notebook with full analysis, including data cleaning, exploratory data analysis, feature engineering, and the machine learning model.
- **`data/`**: Folder containing the dataset (if available).
- **`requirements.txt`**: List of Python dependencies required to run the notebook.

## 🧑‍💻 Analysis Techniques

1. **Data Cleaning**:
   - Handling missing values (e.g., filling in missing data).
   - Correcting data types and removing outliers.
   - Encoding categorical variables for modeling.

2. **Exploratory Data Analysis (EDA)**:
   - Descriptive statistics to understand the distribution of key features.
   - Visualizations (e.g., histograms, bar plots, pie charts) to identify patterns and correlations.

3. **Feature Engineering**:
   - Creating new features to improve model performance.
   - Extraction of useful features like **`num_artists`** and **`is_popular`**.

4. **Machine Learning**:
   - Built a **Linear Regression** model to predict customer spending based on features such as **Age**, **Gender**, and **ProductsPurchased**.
   - The model is evaluated using key metrics like **R-squared** and **Mean Squared Error (MSE)**.

## 📊 Key Visualizations

- **Spending Distribution**: A histogram showing the distribution of customer spending.
- **Customer Segmentation**: Clusters of customers based on their purchasing behavior.
- **Model Evaluation**: Graphs showing the performance of the Linear Regression model.

## 🛠️ Libraries and Tools

- `pandas`: For data manipulation.
- `numpy`: For numerical operations.
- `matplotlib` and `seaborn`: For data visualization.
- `scikit-learn`: For building and evaluating the Linear Regression model.

## 🔍 Key Findings

- **Gender**: Insights on how gender impacts annual spending.
- **Age**: Younger customers tend to spend more in certain categories.
- **Predictive Modeling**: The Linear Regression model was able to predict annual spending with a certain level of accuracy.

## 🚀 Next Steps

- Improve the Linear Regression model by exploring more features or using other regression techniques like **Ridge Regression** or **Lasso Regression**.
- Experiment with other machine learning models (e.g., **Random Forest** or **Gradient Boosting**) to further enhance prediction accuracy.

