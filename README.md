# Ames Housing Sales Prediction

**Project Introduction
This project rigorously analyses the Ames Housing dataset, a rich compilation of housing sales data from Ames, Iowa, between 2006 and 2010, created by Dean De Cock in 2011. With 79 descriptive variables, it provides a unique opportunity to explore and predict housing prices through a multitude of machine learning models.

**Project Goal
The goal of this project is to explore various predictive modeling techniques to accurately forecast housing prices in Ames, providing insights into the housing market during that time.

**Dataset Features
The dataset encompasses a wide range of variables, including:

- General Characteristics: Types and styles of dwellings, ages, and specific features.
- Location Information: Zonal and neighborhood data, along with the proximity to key areas.
- Property Features: Details on lot size, shape, and access.
- Home Features: Information on the number of bedrooms, bathrooms, kitchen quality, and room sizes.
- Basement and Garage Details: Insights into the quality and finish of basements and garages.
- Utilities: Data on available utilities, heating, and cooling systems.
- Quality and Condition: Ratings for the overall material and finish of the houses.

**Methodology and Models
An array of models was utilized for price prediction:

- Linear Regression
- Regularization (Lasso, Ridge)
- Generalized Linear Models (GLM)
- Support Vector Regression (SVR)
- Gradient Boosting
- Bagging
- Random Forest
- Neural Network

**Results and Detailed Insights
- Outliers with large living areas or basements may represent luxury properties with unique features.
- Stable coefficients in models like Ridge regression suggest a balanced influence of predictors.
- Cross-validation RMSE for Gradient Boosting was around 0.11, performing comparably to SVR, Lasso, and Ridge regression models.
- Bagging Regressor's average RMSE was about 0.12, with performance improvements to 0.12 after hyperparameter tuning.
- Gradient Boosting achieved the lowest RMSE value of 0.11, with potential for further improvement through hyperparameter tuning.

**Conclusion
The project tested a variety of models with hyperparameter tuning to determine their predictive power. The Neural Network achieved the best performance with a Training RMSE of 0.55 and a Validation RMSE of 0.82. However, for practical purposes, Gradient Boosting and SVR models were recommended due to their computational efficiency. Both Gradient Boosting and SVR offer good performance but require significant processing power during hyperparameter tuning.
