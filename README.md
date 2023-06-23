# MLNotebookArchives

This repository contains my personal collection of Jupyter notebooks that are used to understand and implement various machine learning algorithms. Each notebook focuses on a specific algorithm or concept in machine learning and contains in-depth explanations, visualizations, and implementation.

## Content

- **Data folder:** This folder contains all the training data used in the models throughout the notebooks.

## Notebook Organization

### Supervised Learning

1. [`singleFeatureLinearRegression.ipynb`](singleFeatureLinearRegression.ipynb)
    - Description: Implementation of Linear Regression with a single input feature using the Sci-kit Learn library. Includes data visualization, model training, and evaluation.

2. [`multipleFeatureLinearRegression.ipynb`](multipleFeatureLinearRegression.ipynb)
    - Description: Expands on the concept of Linear Regression to handle multiple input features. Implemented using the Sci-kit Learn library. Includes techniques for handling multi-dimensional data.

3. [`normalEquationLinearRegression.ipynb`](normalEquationLinearRegression.ipynb)
    - Description: This notebook demonstrates how to perform Linear Regression using the Normal equation, a mathematical approach that calculates the best fit line directly.

4. [`polynomialRegression.ipynb`](polynomialRegression.ipynb)
    - Description: Demonstrates Polynomial Regression, a type of regression that models the relationship between the independent variable and the dependent variable as an nth degree polynomial.

5. [`binaryLogisticRegression.ipynb`](binaryLogisticRegression.ipynb)
    - Description: Implementation of Binary Logistic Regression, a fundamental algorithm for binary classification problems. Includes an explanation and application of the logistic loss function and sigmoid activation function.

6. [`regularizedLinearRegression.ipynb`](regularizedLinearRegression.ipynb)
    - Description: Exploration of Regularized Linear Regression, a version of linear regression that includes a regularization term to prevent overfitting.

7. [`regularizedLogisticRegression.ipynb`](regularizedLogisticRegression.ipynb)
    - Description: This notebook dives into Regularized Logistic Regression, applying a regularization term to the logistic regression algorithm to improve its generalization capabilities.

### Neural Networks

1. [`NeuralNetworkLinearRegression.ipynb`](NeuralNetworkLinearRegression.ipynb)
    - Description: Builds a single-layer neural network for a simple Linear Regression task. A great notebook for understanding how a neural network can be applied to a regression problem.

2. [`NeuralNetworkLogisticRegression.ipynb`](NeuralNetworkLogisticRegression.ipynb)
    - Description: Applies a single-layer neural network to a simple Logistic Regression problem, demonstrating how neural networks can be used for binary classification tasks.

3. [`NeuralNetworkLayers_binaryClassification.ipynb`](NeuralNetworkLayers_binaryClassification.ipynb)
    - Description: Deep dive into a multi-layer neural network for binary classification. This notebook includes:
        - Feature engineering using polynomial features up to degree 6
        - Visualization of activation layers
        - 3D surface graph for decision boundary visualization
        - Building and training of a neural network without the use of high-level libraries
