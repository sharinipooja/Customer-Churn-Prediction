# Customer-Churn-Prediction
# Customer Churn Prediction using Deep Learning

## Overview

This project predicts whether a customer is likely to leave a company using customer demographic and subscription information. A Deep Neural Network (DNN) is trained to classify customers into churn or non-churn categories.

## Features

- Customer data preprocessing
- Label Encoding
- Feature Scaling
- Train-Test Split
- Deep Neural Network model
- Customer churn prediction
- Model evaluation

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- TensorFlow
- Keras

## Dataset Features

- Gender
- Senior Citizen
- Partner
- Monthly Charges
- Tenure
- Churn (Target)

## Workflow

1. Load customer dataset
2. Encode categorical variables
3. Normalize features
4. Split data into training and testing sets
5. Build Deep Neural Network
6. Train the model
7. Evaluate accuracy
8. Predict churn for new customers

## Deep Learning Model

Input Layer

↓

Dense Layer (16 neurons)

↓

Dense Layer (8 neurons)

↓

Output Layer (Sigmoid)

## Installation

```bash
pip install numpy pandas scikit-learn tensorflow keras
```

## Output

- Customer Churn Prediction
- Test Accuracy
- Prediction Probability

## Future Enhancements

- Larger real-world dataset
- Hyperparameter tuning
- Explainable AI (SHAP)
- Web deployment using Flask

