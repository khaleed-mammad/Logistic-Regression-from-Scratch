# Logistic Regression from Scratch

## Description

This project demonstrates the implementation of logistic regression from scratch, focusing on binary classification based on two exam scores. Detailed steps are decribed in the odf file "Report". The key components include:

### 1. Data Preparation  
- Loading and cleaning the dataset using pandas.
- Separating features (`exam_1`, `exam_2`) and labels into `X` and `y`.
- Applying feature scaling using Min-Max normalization for better performance.

### 2. Visualization  
- Scatter plot to visualize the relationship between exam scores and the decision boundary.

### 3. Logistic Regression Implementation  
- **Sigmoid Function**: Calculates the probability of a positive label.  
- **Cost Function**: Measures the error in predictions.  
- **Gradient Descent**: Optimizes weights (`thetas`) by minimizing the cost function over several iterations.  
- **Hyperparameters**: Learning rate (0.1) and iterations (50,000).  
- **Results**: Weights after optimization are `[-11.97, 13.48, 12.86]`.

### 4. Evaluation  
- Training accuracy: 89%.  
- Predictions:  
  - New data points: `[55, 70]` classified as 1, `[40, 60]` classified as 0.  
  - Predictions matched the true labels.

### 5. Logistic Regression Using Libraries  
- Using `sklearn.linear_model` for logistic regression as a comparison.  
- Accuracy on training dataset: 93% (higher than custom implementation due to L2 regularization).  
- Predictions matched custom implementation results.

This project highlights fundamental concepts of logistic regression and compares manual implementation with library-based solutions, emphasizing learning and optimization strategies.
