# House Price Estimation Using Machine Learning

## Project Overview

This project aims to estimate house prices using machine learning models. By analyzing a dataset from Kaggle, the project identifies the most important variables that influence house prices, leveraging the `feature_importance_` hyperparameter. The models used in this project include `LinearRegression` and `RandomForestRegressor`.

## Dataset

- **Source:** The dataset for this project was downloaded from Kaggle.
- **Features:** The dataset includes various features related to the properties of houses, such as size, location, number of rooms, and other relevant attributes.

## Tools & Libraries Used

- **Data Analysis:**
  - `Pandas` for data manipulation and analysis
  - `Matplotlib` for data visualization
- **Modeling:**
  - `LinearRegression` from `sklearn.linear_model`
  - `RandomForestRegressor` from `sklearn.ensemble`
- **Model Evaluation:**
  - `feature_importance_` for analyzing the importance of different features in predicting house prices

## Methodology

1. **Data Exploration:**
   - Conducted an initial exploration of the dataset to understand the distribution of features and the target variable (house prices).

  
2. **Feature Selection:**
   - Used the `feature_importance_` hyperparameter from `RandomForestRegressor` to identify and rank the most important features that influence house prices.

 
3. **Model Training:**
   - Trained a `LinearRegression` model to establish a baseline for house price prediction.
   - Trained a `RandomForestRegressor` model to capture more complex relationships between the features and the target variable.

4. **Model Evaluation:**
   - Evaluated the performance of both models by comparing predicted prices with actual prices using metrics such as R-squared and Mean Absolute Error (MAE).


## Results

- The `RandomForestRegressor` model provided a more accurate prediction of house prices compared to the `LinearRegression` model.
- The feature importance analysis highlighted key factors such as location, size, and the number of rooms as the most influential variables in determining house prices.

## Conclusion

This project successfully demonstrated the application of machine learning models to estimate house prices. By analyzing feature importance, valuable insights were gained into the factors that drive house prices, which can inform future real estate decisions.

## Future Work

- Experiment with additional models and hyperparameter tuning to further improve prediction accuracy.
- Explore the use of ensemble methods to combine multiple models for better performance.
- Consider incorporating additional features, such as market trends and economic indicators, to enhance the model's predictive power.

