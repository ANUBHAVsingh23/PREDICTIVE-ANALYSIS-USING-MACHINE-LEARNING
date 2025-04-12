# CODTECH Internship - PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: ANUBHAV SINGH

*INTERN ID*: CT06DA708

*DOMAIN*: DATA ANALYTICS

*DURATION*: 6 WEEEKS

*MENTOR*: NEELA SANTOSH


## Task 2: PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING Housing Price Prediction - Regression and Classification Models

### Overview

This project explores building machine learning models using PySpark MLlib to predict housing prices. It includes two models: a Regression model to predict the continuous `median_house_value` and a Classification model to predict house price categories (low, mid, high). This demonstrates predictive analysis and model evaluation in PySpark.

### Tasks Performed

*   Installed PySpark library.
*   Created a Spark Session.
*   Loaded the `housing.csv` dataset into a Spark DataFrame.
*   **Regression Model:**
    *   Selected features and assembled them into a feature vector.
    *   Split the data into training and testing sets.
    *   Trained a Linear Regression model to predict `median_house_value`.
    *   Evaluated the Regression model using RMSE and R² metrics.
*   **Classification Model:**
    *   Created a new categorical label column `price_label` based on `median_house_value` (low, mid, high price categories).
    *   Reused the same features and assembled them into a feature vector.
    *   Split the data into training and testing sets.
    *   Trained a Logistic Regression model to predict `price_label` (price category).
    *   Evaluated the Classification model using accuracy metric.
*   Summarized key insights from both Regression and Classification models.

### Code and Resources Used

*   **Programming Language:** Python
*   **Libraries:** PySpark, scikit-learn
*   **Dataset:** `housing.csv` (California Housing dataset)
*   **Notebooks:**
    *   [Link to your Task 2 Notebook (task2.ipynb)](task2.ipynb)

### Results and Insights

*   **Linear Regression Model:**  Demonstrates how features like income and housing characteristics can be used to predict house values. Achieved an RMSE of approximately 76768 and an R² of 0.547, indicating moderate predictive power.
*   **Classification Model:**  Simplifies the prediction task by categorizing house prices. The Logistic Regression model achieved a classification accuracy of approximately 69.5%, showing reasonable performance in categorizing house prices.
*   **Model Effectiveness:** Both Regression and Classification models provide valuable insights, with Regression giving a continuous price prediction and Classification offering a categorical understanding of price ranges.

### How to Run (Optional)

The code is designed to be run in Google Colab. Simply open the `task2.ipynb` notebook in Colab and run the cells sequentially.
