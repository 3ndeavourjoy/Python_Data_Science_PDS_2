# California Housing Price Prediction

This project predicts California housing prices using machine learning. It compares Linear Regression and Random Forest Regression models on the California housing dataset.

## Key Features

* **Dataset:** California Housing dataset from scikit-learn.
* **Models:** Linear Regression and Random Forest Regression.
* **Preprocessing:** Feature scaling using StandardScaler and train-test split (80/20).
* **Evaluation:** Mean Squared Error (MSE), R-squared (R2), and 5-fold cross-validation.

## Results

| Model                | MSE   | R2    | Mean CV R2 |
|---------------------|-------|-------|------------|
| Linear Regression    | 0.524 | 0.612 | 0.609      |
| Random Forest Regression| 0.217 | 0.805 | 0.801      |

Random Forest Regression significantly outperformed Linear Regression, demonstrating better predictive accuracy.
