# Classification Chapter Summary

This chapter covers the theory and practice of classification in machine learning. Key topics include:

- **Overview:** Classification is the task of assigning labels to input data based on learned decision boundaries. Recommended literature includes Bishop's "Pattern Recognition and Machine Learning" (sections on discriminant functions, generative models, kernels, committees, boosting, and tree-based models).

- **Decision Trees:** Decision trees are interpretable models that split data based on feature values, leading to a tree structure of decisions and predictions. The CART algorithm is a common method for constructing binary trees using impurity measures. Decision trees can output class probabilities, not just labels, and are especially useful for domains requiring interpretability.

- **Mathematical Formulation:** A decision tree recursively applies decision functions $q(\mathbf{x})$ to split data, with leaf nodes providing class probability vectors. The recursive structure allows for complex, hierarchical decision boundaries.

- **Evaluation and Bias-Variance Tradeoff:** The bias-variance tradeoff in classification decomposes prediction error into noise, bias, and variance. The noise is inherent to the data, bias measures systematic error, and variance measures model sensitivity to training data. Overfitting and underfitting are controlled by model complexity and hyperparameters (e.g., tree depth, number of neighbors in k-NN, regularization in SVMs).

- **Hyperparameters:** The chapter details how key hyperparameters for common classifiers (k-NN, Naive Bayes, Decision Trees, Random Forests, SVMs) affect overfitting and underfitting.

Mathematical notation and figures are used throughout to clarify concepts such as the recursive definition of decision trees and the bias-variance decomposition for classification.
