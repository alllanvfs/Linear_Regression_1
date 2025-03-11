# Linear Regression Project - My First Model

This repository contains the code for my first linear regression model, developed in Python using the scikit-learn library. The main goal of this project is to predict continuous values based on a given dataset, serving as a foundation for future improvements and experimentation with machine learning techniques.

## Technologies and Libraries Used

- **Python:** Programming language used for developing the project.
- **pandas:** For data manipulation and analysis.
- **numpy:** For numerical operations and array manipulation.
- **scikit-learn:** Library used for creating the linear regression model, data preprocessing, splitting the data into training and testing sets, and evaluating the model's performance.

## Project Features

- **Loading and Preparing the Data:**  
  The code reads a dataset from a CSV file, separating the features (independent variables) and the target (the variable to be predicted).

- **Splitting the Data:**  
  The data is split into training and testing sets using the `train_test_split` function to ensure proper evaluation of the model with data it has never seen during training.

- **Preprocessing:**  
  Data scaling is applied using the `StandardScaler` to standardize the features, ensuring all variables have the same scale, which is essential for machine learning models.

- **Model Training:**  
  We use the linear regression algorithm (`LinearRegression`) from scikit-learn to train the model with the training data.

- **Model Evaluation:**  
  The model's performance is evaluated using metrics such as Mean Squared Error (MSE) and R-squared (R²). These metrics help understand the magnitude of errors and the explanatory power of the model.

- **Predictions:**  
  At the end of the code, the model makes predictions for some examples from the test set, allowing for a direct comparison between predicted and actual values.

## Next Steps and Possible Improvements

- **Error Analysis:** Investigate cases where the model showed the largest discrepancies between predicted and actual values, identifying possible improvements or the need for further data treatments.
- **Experimenting with Regularization Techniques:** Evaluate models like Ridge or Lasso to address potential multicollinearity issues.
- **Integration with Other Algorithms:** Explore other regression algorithms or even non-linear approaches to compare performance and increase model robustness.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/alllanvfs/Linear_Regression_1.git
