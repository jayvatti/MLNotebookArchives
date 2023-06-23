# MLNotebookArchives

This repository contains a collection of Jupyter notebooks, each highlighting the application and understanding of a distinct machine learning model, from the basics to the more sophisticated.

## Content

- **Data folder:** A curated repository of datasets, serving as the foundation and fuel for the models crafted in these notebooks.

## Notebook Structure

### Supervised Learning

1. [`singleFeatureLinearRegression.ipynb`](singleFeatureLinearRegression.ipynb)
    - Description: 
        - A beginner's journey into Linear Regression with a single input feature. 
        - Implementation with Sci-kit Learn library.
        - Another version without any libraries.
        - Plots of cost functions for learning rate selection.

2. [`multipleFeatureLinearRegression.ipynb`](multipleFeatureLinearRegression.ipynb)
    - Description: 
        - Stepping up to multi-feature Linear Regression. 
        - Implementation using Sci-kit Learn. 
        - Another version without libraries.
        - Includes cost function plots to guide the choice of learning rate.

3. [`normalEquationLinearRegression.ipynb`](normalEquationLinearRegression.ipynb)
    - Description: Ditching iterations for equations, this notebook presents Linear Regression via the Normal equation. 

4. [`polynomialRegression.ipynb`](polynomialRegression.ipynb)
    - Description: Straight lines are too mainstream! This notebook explores Polynomial Regression using Sci-kit Learn. 

5. [`binaryLogisticRegression.ipynb`](binaryLogisticRegression.ipynb)
    - Description: Flirting with classification, this notebook delves into Binary Logistic Regression using Logistic Loss and Sigmoid Functions. 

6. [`regularizedLinearRegression.ipynb`](regularizedLinearRegression.ipynb)
    - Description: 
        - Regularization to the rescue! This notebook presents Regularized Linear Regression.
        - Both library-based and bare-bones implementations are available.
        - Cost function plots to select the best learning rate and lambda values.

7. [`regularizedLogisticRegression.ipynb`](regularizedLogisticRegression.ipynb)
    - Description: 
        - The sequel to regularized linear regression, featuring Regularized Logistic Regression. 
        - Implementations both with and without libraries.
        - Cost function plots to guide the choice of learning rate and lambda values.

### Neural Networks

1. [`NeuralNetworkLinearRegression.ipynb`](NeuralNetworkLinearRegression.ipynb)
    - Description: From regressions to neurons, this notebook implements a single-layer neural network for Linear Regression.

2. [`NeuralNetworkLogisticRegression.ipynb`](NeuralNetworkLogisticRegression.ipynb)
    - Description: Continuing the neural exploration, this notebook applies a single-layer neural network for Logistic Regression. 

3. [`NeuralNetworkLayers_binaryClassification.ipynb`](NeuralNetworkLayers_binaryClassification.ipynb)
    - Description: Unleashing the power of deep learning, this notebook explores a multi-layer neural network for binary classification, featuring:
        - Feature engineering using polynomial features up to degree 6.
        - Visualizations of activation layers and 3D surface plots. 
        - Building a neural network from scratch, no high-level libraries involved.
