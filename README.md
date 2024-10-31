# Titanic Survival Prediction Project

## Overview
This project aims to create a simple statistical model to predict the survivals of passengers in the Titanic drowning tragedy using the Titanic dataset. The model employs a machine learning approach with a focus on interpretability and predictive performance.

## Dataset
The dataset used for this project is the well-known Titanic dataset, which includes information about passengers on board the ill-fated ship. The dataset contains several features associated with each passenger, which are instrumental in predicting their chances of survival during the disaster.

## Key Features
- **PassengerId**: A unique identifier for each passenger.
- **Pclass**: The class of the ticket purchased by the passenger (1st, 2nd, or 3rd).
- **SibSp**: The number of siblings or spouses aboard the Titanic.
- **Parch**: The number of parents or children aboard the Titanic.
- **Fare**: The amount of money paid for the ticket.

## Target Variable
- **Survived**: This binary variable indicates whether a passenger survived (1) or did not survive (0).

## Model
For the predictive modeling task, we utilized the `RandomForestClassifier`, a powerful ensemble learning method known for its robustness and accuracy in classification challenges. 

## Model Evaluation
The performance of the model was evaluated using several metrics:
- **Precision**: 1.00
- **Recall**: 0.77
- **F1-score**: 0.80
- **Accuracy**: 0.78

These metrics suggest that while the model is highly precise in predicting survivors, there is potential for enhancement in recall. This indicates a balanced approach in identifying both true positives and false negatives, making the model quite effective for this classification task.

---

Feel free to contribute, provide feedback, or suggest enhancements to improve the model!
