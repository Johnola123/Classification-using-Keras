# Classification-using-Keras





# Objective:
Predict whether a customer will churn using a deep learning model implemented in Keras.

# Workflow Summary:
## 1. Data Cleaning & Preparation
Preprocessed features:

Converted categorical to numerical.

Scaled numerical variables using normalization.

## 2. Model Architecture
Built a neural network using Keras.Sequential():

Input layer

Dense hidden layers with ReLU activations

Output layer with Sigmoid for binary classification

## 3. Training
Loss Function: binary_crossentropy

Optimizer: adam

Epochs: 100+ with batch size tuned

Included validation_split to monitor overfitting.

## 4. Evaluation
Used:

Training/Validation Accuracy

Training/Validation Loss

Accuracy curves to assess performance

#  Results:
Final Training Accuracy: ~87.5%

Validation Accuracy: ~86.3%

Overfitting was minimal, with close training/validation curves.
