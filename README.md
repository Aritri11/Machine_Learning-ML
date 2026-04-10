# Machine Learning Lab Repository

This repository is a structured, lab-wise collection of machine learning implementations covering foundational mathematics, supervised learning, model evaluation, ensemble methods, SVMs, clustering, PCA, and probabilistic models.

## Repository Structure

The project is organized into numbered lab folders:

- `Lab1` to `Lab24`, and `Lab26`
- combined folders such as `Lab4&5` and `Lab10&11`
- each lab contains one or more Python scripts (`.py`)
- several labs also include datasets (`.csv`)

## Topics Covered

### 1) Foundations and Mathematical Concepts
- Matrix operations, plotting, Gaussian distribution, derivatives
- Hessian, eigenvalues, quadratic forms, positive definiteness

### 2) Regression
- Linear regression using scikit-learn
- Linear regression from scratch (gradient descent / SGD)
- Regularization concepts and model behavior

### 3) Classification
- Logistic regression (scikit-learn and from scratch)
- Decision trees (classification and regression, including from scratch)
- Evaluation metrics: confusion matrix, precision, recall, F1, ROC, AUC

### 4) Validation and Model Selection
- Train/validation/test splitting
- K-Fold and Stratified K-Fold cross-validation
- Bias-variance, underfitting vs overfitting analysis

### 5) Ensemble Learning
- Bagging (scikit-learn and custom)
- Random Forest
- AdaBoost (including SAMME-style custom implementation)
- Gradient Boosting and XGBoost with hyperparameter tuning

### 6) Kernel Methods and SVM
- Linear, polynomial, and RBF kernels
- Kernel transformation and decision boundary visualization

### 7) Unsupervised Learning and Dimensionality Reduction
- K-Means clustering (scikit-learn and from scratch)
- Hierarchical clustering
- PCA (visual analysis, variance explanation, downstream classification)

### 8) Generative / Probabilistic Models
- Joint probability based classifier
- Bernoulli Naive Bayes for spam classification
- Multiclass image classification example using KNN

## Datasets and Inputs

The repository uses:
- local CSV datasets included in lab folders (e.g., Sonar, Breast Cancer variants)
- built-in datasets from scikit-learn/statsmodels/ISLP
- some scripts reference external/local absolute paths (update paths before running)

## How to Use

1. Navigate to a lab folder.
2. Open the corresponding `.py` file.
3. Install required Python packages (`numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, etc.).
4. Run the script with Python:

```bash
python <script_name>.py
```

## Notes

- This repository is learning-oriented and intentionally includes both **library-based** and **from-scratch** implementations.
- Several lab-level `README.md` files are placeholders.
- Lab numbering skips `Lab25` in the current version.
