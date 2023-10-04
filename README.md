# Price_Prediction
I am testing different algorithms to determine the one with the lowest error rate.

Mobile Phone Price Prediction

This is a simple README file for the "Mobile Phone Price Prediction" project. We aim to predict the price range of smartphones based on various features. Here's a brief overview:

Overview
We have created a predictive model to estimate the price range of mobile phones. The price range is categorized into four levels:
0: Low Cost
1: Medium Cost
2: High Cost
3: Very High Cost

We evaluate the model's performance using F1 scores with the following interpretation:
F1 Score 0.9 - 1.0: Very Good
F1 Score 0.8 - 0.9: Good
F1 Score 0.5 - 0.8: OK
F1 Score Below 0.5: Not Good

Key Steps
The project follows these key steps:

1. Data Preparation
We import the necessary libraries and load the dataset with features like battery power, RAM, camera quality, and more.

2. Data Exploration
We explore the dataset for any missing values, or duplicates, and examine data types.

3. Data Preprocessing
We split the data into training and testing sets, preparing it for model training.

4. Modelling & Evaluation
We build and evaluate three models: K-Nearest Neighbors, Decision Tree, and Random Forest. We measure their performance using F1 scores.

5. Model Deployment
We choose the best-performing model (K-Nearest Neighbors) and deploy it. The model is saved as 'model.pkl', and a Streamlit application is provided for easy use.
For detailed code and implementation, please refer to the project repository.
