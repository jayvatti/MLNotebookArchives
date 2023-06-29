# [MLNotebookArchives](https://jayvatti.github.io/MLNotebookArchives/)

This repository contains a collection of Jupyter notebooks, each highlighting the application and understanding of a distinct machine learning model, from the basics to the more sophisticated. (In Progress)

## Content

- **[`Data folder`](/data/ReadMe.md):** A curated repository of datasets, serving as the foundation and fuel for the models crafted in these notebooks.

## Notebook Structure

### Supervised Learning

1. [`singleFeatureLinearRegression.ipynb`](singleFeatureLinearRegression.ipynb)
    - Description: 
        - A beginner's journey into Linear Regression with a single input feature. 
        - Implementation with Sci-kit Learn library.
        - Another version without any libraries.
        - Plots of cost functions for learning rate selection.
        - Bonus: A sketched line of best fit! (With and without Z-Score Normalization)
        - Dataset: [height_weight.csv](/data/height_weight.csv)
          


2. [`multipleFeatureLinearRegression.ipynb`](multipleFeatureLinearRegression.ipynb)
    - Description: 
        - Stepping up to multi-feature Linear Regression. 
        - Implementation using Sci-kit Learn. 
        - Another version without libraries.
        - Includes cost function plots to guide the choice of learning rate.
        - New: Added plots comparing the predictions from the SciKit Learn version and the version without libraries. Also included are plots comparing each method with the actual predictions.
        - Dataset: [multipleFeatures.csv](/data/multipleFeatures.csv) - Because one feature is too mainstream!



3. [`normalEquationLinearRegression.ipynb`](normalEquationLinearRegression.ipynb)
    - Description:
        - Ditching iterations for equations, this notebook presents Linear Regression via the Normal equation.
        - Employs the same [dataset](/data/height_weight.csv) as the singleFeatureLinearRegression notebook
        - Graphical representations may be missing, but the calculated weights and bias are similar to the ones from the gradient descent approach in [singleFeatureLinearRegression.ipnyb](singleFeatureLinearRegression.ipynb)



4. [`polynomialRegression.ipynb`](polynomialRegression.ipynb)
    - Description: Straight lines are too mainstream! This notebook explores Polynomial Regression using Sci-kit Learn.
        - Dataset: [polyRegression.csv](/data/polyRegression.csv) 



5. [`binaryLogisticRegression.ipynb`](binaryLogisticRegression.ipynb)
    - Description: Flirting with classification, this notebook delves into Binary Logistic Regression using Logistic Loss and Sigmoid Functions.
    - Updated: Now includes a visualization of the sigmoid function and classification boundary, helping to understand how well the model separates classes. Classifying has never been so visually appealing!
        - Dataset: [logisticRegression.csv](/data/logisticRegression.csv)



6. [`regularizedLinearRegression.ipynb`](regularizedLinearRegression.ipynb)
    - Description: 
        - Regularization to the rescue! This notebook presents Regularized Linear Regression.
        - Both library-based and bare-bones implementations are available.
        - Cost function plots to select the best learning rate and lambda values.
        - New: Added a plot to show the predictions of the custom model versus the original data, and another plot to compare the SciKit Learn version with the version without libraries.
        - Dataset: [multipleFeatures.csv](/data/multipleFeatures.csv) 



7. [`regularizedLogisticRegression.ipynb`](regularizedLogisticRegression.ipynb)
    - Description: 
        - The sequel to regularized linear regression, featuring Regularized Logistic Regression. 
        - Implementations both with and without libraries.
        - Cost function plots to guide the choice of learning rate and lambda values.
        - Dataset: [logisticRegressionCircular.txt](/data/logisticRegressionCircular.txt) 

---

### Neural Networks

1. [`NeuralNetworkLinearRegression.ipynb`](NeuralNetworkLinearRegression.ipynb)
    - Description: 
        - From regressions to neurons, this notebook implements a single-layer neural network for Linear Regression.
        - A regression line is sketched to highlight the model's predictions.
        - Dataset: [linearRegressionSimple.csv](/data/linearRegressionSimple.csv) 



2. [`NeuralNetworkLogisticRegression.ipynb`](NeuralNetworkLogisticRegression.ipynb)
    - Description: 
        - Continuing the neural exploration, this notebook applies a single-layer neural network for Logistic Regression. 
        - A sketched sigmoid function after fine-tuning the weights and biases using Sci-kit learn.
        - Notably, it focuses on tumor classification - the model might not cure cancer, but it sure can classify it!
        - Dataset: [logisticRegressionTumorSingle.csv](/data/logisticRegressionTumorSingle.csv) - On a mission to segregate tumors!



3. [`NeuralNetworkLayers_binaryClassification.ipynb`](NeuralNetworkLayers_binaryClassification.ipynb)
    - Description: Unleashing the power of deep learning, this notebook explores a multi-layer neural network for binary classification, featuring:
        - Feature engineering using polynomial features up to degree 6.
        - Visualizations of activation layers and 3D surface plots. 
        - Building a neural network from scratch, no high-level libraries involved.
        - Dataset: [logisticRegressionCircular.txt](/data/logisticRegressionCircular.txt) 

