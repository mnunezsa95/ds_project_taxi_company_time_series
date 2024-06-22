# Sweet Lift Taxi Demand Prediction

## Overview
Sweet Lift Taxi, a leading transportation service provider, has collected extensive historical data on taxi orders at various airports. To optimize service delivery during peak hours, the company aims to develop a predictive model that accurately forecasts the number of taxi orders for the upcoming hour. This model will help attract more drivers during high-demand periods, ensuring efficient and reliable service.

## Description
The project focuses on creating a predictive model to forecast hourly taxi orders. By analyzing historical data and exploring various machine learning algorithms, the goal is to develop a model that achieves a Root Mean Squared Error (RMSE) of no more than 48 on the test set. Achieving this level of accuracy will allow Sweet Lift Taxi to anticipate demand fluctuations and make informed decisions about resource allocation, enhancing both driver satisfaction and customer experience.

## Objectives
- Primary Objective: Develop a robust predictive model with an RMSE of no more than 48 on the test set.
- Data Analysis: Conduct a comprehensive analysis of historical data, including data preprocessing and feature engineering.
- Model Exploration: Evaluate various machine learning algorithms to identify the best predictive model.
- Performance Evaluation: Rigorously assess model performance to ensure it meets the specified accuracy criteria.

## Libraries
The project utilized the following libraries:
- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations and handling arrays.
- Scikit-Learn: For implementing machine learning algorithms and model evaluation.
- Matplotlib: For data visualization and plotting graphs.
- Statsmodels: For statistical modeling and analysis.

These libraries were instrumental in data preprocessing, model training, and evaluation, ensuring the development of an accurate and efficient predictive model.

## Conclusion
After training and evaluating six different models based on their RMSE values, it was found that all models performed closely within a range of ±4.3669, effectively minimizing prediction errors. The Decision Tree Regressor, Random Forest Regressor, and Moving Average (MA) Model were selected for further evaluation using test data. Each model demonstrated distinct strengths:

- Decision Tree Model: Quick training and moderate RMSE with rapid prediction speed.
- Random Forest Model: Lowest RMSE and excellent prediction speed, slightly slower training.
- Moving Average Model: Fastest prediction speed despite higher RMSE and slowest training.

By identifying the optimal model based on performance and computational efficiency, Sweet Lift Taxi aims to implement a robust predictive tool. This tool will effectively anticipate fluctuations in demand, enabling strategic decision-making to optimize resource allocation and service delivery during peak hours, thereby enhancing overall service quality and customer satisfaction.
