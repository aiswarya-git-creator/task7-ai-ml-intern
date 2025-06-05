# Objective

The goal of this task was to apply Support Vector Machines (SVM) for both linear and non-linear binary classification using the Breast Cancer dataset. Key steps included data preparation, model training with different kernels, hyperparameter tuning, visualization of decision boundaries, and model evaluation.

# What We Did

#  Data Preparation
   * Loaded the Breast Cancer dataset.
   * Selected two features (radius_mean and texture_mean) for 2D visualization.
   * Converted diagnosis labels into numeric form (M = 1, B = 0).
   * Split the data into training and testing sets.
   * Standardized feature values for better SVM performance.
# Training SVM Models
   * Trained two SVM classifiers: one with a linear kernel and another with an RBF (Radial Basis Function) kernel.
   * Visualized their decision boundaries on the training data to understand how each kernel separates classes.
# Hyperparameter Tuning
   * Used Grid Search with cross-validation to find the best hyperparameters (C and gamma) for the RBF kernel SVM.
   * Identified the optimal parameters that maximize classification performance.
# Model Evaluation
   * Evaluated the tuned model on the test set to measure its accuracy.
   * Performed 5-fold cross-validation on the entire dataset to estimate the model’s robustness and average accuracy.

# Outputs 

* Decision Boundary Visualization
* Best Hyperparameters from Grid Search
* Accuracy on Test Set
* Cross-validation Scores
