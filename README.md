# SpaceX Landing Model

## Overview
The **SpaceX Landing Model** is a machine learning project aimed at predicting the successful landing of SpaceX rockets based on various features such as flight number, payload mass, launch site, and other attributes. The goal of this project is to predict whether a rocket will successfully land (1) or fail (0) using historical flight data. This is a binary classification problem where the objective is to classify rocket landings as successful or unsuccessful.

The dataset consists of several features related to rocket launches, and multiple machine learning models were trained to predict landing success.

## Technologies Used
- **Python** for implementation
- **Scikit-learn** for machine learning algorithms and model evaluation
- **Pandas** for data manipulation and cleaning
- **NumPy** for numerical operations
- **Matplotlib** and **Seaborn** for data visualization

## Results
After evaluating several machine learning models, the **Random Forest** model provided the best performance with an **accuracy of 90.5%**. This model demonstrated its ability to predict rocket landings with high accuracy.

- **Logistic Regression**: 85.5% accuracy
- **Support Vector Machine (SVM)**: 82.3% accuracy
- **Decision Tree**: 80.4% accuracy
- **Random Forest**: 90.5% accuracy (best model)

The **Random Forest model** outperformed the others in terms of accuracy, precision, and recall, making it the most reliable choice for predicting SpaceX rocket landings.

## Conclusion
This project demonstrates how machine learning can be applied to predict rocket landing success, using features like flight number, payload mass, and launch site. The **Random Forest** model proved to be the best-performing model for this task, achieving high accuracy and providing reliable predictions for future rocket landings.

This project is a great example of how data science and machine learning can be applied to real-world problems, and it showcases the ability of machine learning models to make predictions based on historical data.
