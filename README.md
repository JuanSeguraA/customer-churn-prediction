# Customer Churn Prediction

## Project Overview

This project predicts whether customers of a telecom company are likely to churn (stop their subscription) using machine learning. It involves data preprocessing, exploratory data analysis, feature engineering, model training, hyperparameter tuning, and overall evaluation. 

The final model can also predict churn probability for new customers in real time.

## Installation 

git clone https://github.com/JuanSeguraA/customer-churn-prediction.git

cd customer-churn-prediction

pip install -r requirements.txt

## Data Source

[Kaggle: Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Workflow

Day 1 - Data cleaning 

Day 2 - Data Preprocessing

Day 3 - EDA & Feature Engineering

Day 4 - Model training & hyperparameter tuning

Day 5 - Evaluation (confusion matrix, ROC curve, AUC, precision/recall, F1)

Day 6 - Finalize pipeline

## Project Insights

- Most churn occurs among customers with shorter tenure, highlighting early-stage churn risk.

- Month-to-month contracts have higher churn rates compared to one- or two-year contracts.

- Higher monthly charges total charges correlate with increased churn likelihood.

## Model Performance 

Best model: Random Forest (tuned)

ROC AUC: 0.84

## Visualization

The project includes visualizations such as:

- Bar chart

- Histogram

- KDE plot

- Correlation heatmap

- Confusion matrix

- ROC curve

Here are some examples:

<img src="images\confusionmatrix.png" alt="Confusion matrix" width="500">
<img src="images\correlationheatmap.png" alt="Correlation heatmap" width="479">

<img src="images\monthlychargeschurn.png" alt="KDE plot" width="500">
<img src="images\roccurve.png" alt="ROC curve" width="500">

## Conclusion

This project demonstrates how machine learning can be used to predict customer churn based on key features. It highlights the power of data-driven insights to help businesses identify at-risk customers and take proactive retention measures.


## Author 

Juan Segura 
<br>
[Connect with me on LinkedIn](https://www.linkedin.com/in/juan-segura-a364822ab?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BnEzclJQLR8axb35ie6sEWQ%3D%3D)
