# EE8603 - Bike Sharing - Regression

# Abstract
In this project, I aimed to analyze and predict bike rental counts using various weather and temporal features from a provided dataset. The dataset included information such as date, time, temperature, humidity, wind speed, and whether it was a holiday, among other factors. Our objective was to identify which factors most significantly influenced bike rental patterns and to build a model that could accurately predict rental counts.

To achieve this, I first preprocessed the data, encoding categorical variables, and scaling numerical features. then I used PyCaret, an automated machine-learning library, to compare different regression models. Our comparison included models like Linear Regression, Decision Tree, Random Forest, and advanced ensemble methods like CatBoost, XGBoost, LR, and LightGBM.

The final results indicated that the CatBoost Regressor outperformed other models, achieving the lowest values in Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE), and the highest R-squared value. This suggests that CatBoost was the most accurate and consistent in predicting bike rental counts. Given these results, it was selected as the final model. The effectiveness of CatBoost in this context can be attributed to its ability to handle categorical data efficiently and its robustness against overfitting, making it well-suited for this dataset with diverse features and complex relationships.

Overall, this project demonstrated the utility of machine learning in understanding and forecasting consumer behavior in relation to environmental and temporal factors. The success of the CatBoost model in this scenario highlights the potential of advanced ensemble techniques in predictive analytics.

# Video Link
https://www.youtube.com/watch?v=yHO6jj0U81k&t=17s
