 Bank Marketing ML App

## Overview

This project predicts whether a customer will subscribe to a bank term deposit based on marketing campaign data. Machine learning algorithms were used to analyze customer information and build predictive models. The goal of the project is to help banks identify potential customers who are more likely to subscribe to their services.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Streamlit

## Machine Learning Models

Four machine learning algorithms were implemented and compared to determine the best performing model:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

After evaluation, **Random Forest achieved the best performance** among the models.

## Project Features

* Data preprocessing and cleaning
* Feature selection and transformation
* Training and evaluation of multiple machine learning models
* Model comparison based on performance metrics
* Interactive GUI built using Streamlit for predictions

## How to Run the Project

1. Install the required libraries:

```
pip install -r requirements.txt
```

2. Run the Streamlit application:

```
streamlit run app.py
```

## Project Structure

```
Bank-Marketing-ML-App
│
├── app.py
├── model.pkl
├── notebook.ipynb
├── dataset.csv
├── requirements.txt
└── README.md
```

## Conclusion

This project demonstrates how machine learning can be applied to marketing data to predict customer behavior. By comparing multiple algorithms, the Random Forest model provided the best results for predicting customer subscription.

Dataset: https://archive.ics.uci.edu/ml/datasets/bank+marketing
