# Yes-Bank-Stock-Closing-Price-Prediction
## Introduction

This project aims to predict the monthly closing stock prices of Yes Bank, analyzing the impact of events like the fraud case involving Rana Kapoor. The dataset includes monthly stock prices since the bank's inception, covering closing, opening, highest, and lowest prices.

## Prediction Models

Three models were developed to predict Yes Bank's stock prices:

- **Ridge Regression**:
  - Implements linear regression with regularization to prevent overfitting.
  - Suitable for datasets with multicollinearity issues.

- **Random Forest** (Top Performing Model):
  - Utilizes ensemble learning to aggregate predictions from multiple decision trees.
  - Effective for handling high-dimensional data and capturing complex relationships.

- **XGBoost Regressor**:
  - Uses gradient boosting to build an ensemble of decision trees sequentially.
  - Known for its high accuracy and adaptability to various data types.

## Evaluation Metrics

Models were evaluated using five key metrics to assess performance:

- **MSE (Mean Squared Error)**:
  - Measures the average squared difference between predicted and actual values.
  - Lower values indicate better model performance.

- **RMSE (Root Mean Squared Error)**:
  - RMSE is the square root of MSE, providing a measure of prediction accuracy in the same units as the target variable.
  - Lower RMSE values signify better model accuracy.

- **R2 Score (Coefficient of Determination)**:
  - R2 score quantifies the proportion of variance in the dependent variable explained by the independent variables.
  - A score of 1 indicates a perfect fit, while lower values indicate less effective models.

- **Adjusted R2**:
  - Adjusts R2 for the number of predictors in the model, penalizing excessive features.
  - Provides a more realistic measure of model fit, particularly useful for comparing models with different numbers of predictors.

- **MAE (Mean Absolute Error)**:
  - MAE measures the average magnitude of errors in a set of predictions, without considering their direction.
  - Provides a straightforward interpretation of prediction errors.

## Conclusion and Future Considerations

The Random Forest model emerged as the top-performing model, achieving high accuracy in predicting Yes Bank stock prices. Future enhancements could include exploring daily-level data and incorporating additional features like holidays and events for more accurate predictions.
