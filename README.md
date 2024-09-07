

## Problem Overview 🤩
The e-commerce platform is experiencing difficulties in accurately predicting customer ratings, leading to decreased customer satisfaction, reduced sales, and a negative impact on brand reputation. Although customer rating data is available, the current system fails to properly analyze and interpret it, causing imprecise predictions. This highlights the need for a more advanced machine learning model capable of accurately analyzing rating data to predict customer ratings, ultimately enhancing customer satisfaction, boosting sales, and strengthening brand reputation.

## Goal 🤔
Achieve an accuracy of at least 80% in predicting customer ratings within a year based on specific order information. This will empower businesses to make informed, data-driven decisions regarding their products, marketing, and customer service.

## Data Source 📅
The dataset was sourced from the <a href="https://www.kaggle.com/datasets/prachi13/customer-analytics">E-Commerce Shipping Data</a> available on Kaggle.

## Methods Used 🕵️‍♀️
To predict if a customer would give a rating of 1, we remapped ratings 2 to 5 as 0, representing any rating other than 1. This converted the task into a <b>binary classification</b> rather than a multiclass classification problem.

## Outcome 🔎
The final model used was a k-Nearest Neighbors (KNN) classifier. It achieved an accuracy of approximately 77.60% on the test data. Additionally, a Flask application with a user-friendly interface was developed, which can be executed on a local machine (as shown in the video below).

https://user-images.githubusercontent.com/57357735/230870228-6b66ab5c-1b04-485e-86e8-bd7b81fd34eb.mp4

## Suggestions 📥
* Experiment with other classification algorithms such as support vector machine, random forest classifier, and logistic regression.
* Apply Randomized Search or Grid Search to fine-tune hyperparameters and potentially improve accuracy.
* Address class imbalance issues using techniques like SMOTE, SMOTE-TOMEK, ADASYN, or SMOTE-ENN.
* Consider developing a multiclass classification model with this dataset, where you wouldn't need to remap ratings 2 to 5 as 0. This would allow the model to predict whether a customer will give a rating of 1, 2, 3, 4, or 5 specifically, rather than just predicting whether they will give a rating of 1 or not.


