# California Housing Value Prediction

The objective of this project is to develop a machine learning model capable of predicting housing values in California. Utilizing a detailed dataset on demographic and geographic characteristics, we aim to provide accurate estimates of property values, which can be useful for real estate agencies, buyers, sellers, and other stakeholders in the housing market.

![image](https://github.com/JuanF3/Housing-Regression-Task/assets/60745140/5823e66e-6708-4478-8264-fe5bf6b33808)
https://public.tableau.com/views/CaliforniaHousingPrices_17169037313240/Sheet1?:language=en-GB&:sid=&:display_count=n&:origin=viz_share_link

## Dataset
The project is based on the well-known "California Housing" dataset, which contains information on various characteristics of different districts in California. The main features of the dataset include:

* Median Age of Houses.
* Average Household Income.
* Total Population of the District.
* Total Number of Households.
* Total Number of Rooms.
* Total Number of Bedrooms.
* Proximity to the Ocean (categories like: "inland", "near ocean", "near bay").
* Median House Value (target variable).

  ## Methodology

1. Data Exploration and Preprocessing:
* Descriptive analysis of dataset features.
* Handling missing values and outliers.
* Encoding categorical variables and scaling numerical features.
* Correlation analysis to identify relationships between variables.

2.Modeling:
* Implementation of various machine learning algorithms, including:
* Linear Regression.
* Random Forest Regressor.
* Support Vector Regressor (SVR) with different kernels (linear, polynomial, RBF).
* Hyperparameter tuning using techniques like Grid Search and Random Search.
* Model evaluation through cross-validation.

3.Evaluation and Validation:
* Using metrics such as RMSE (Root Mean Squared Error), to assess model accuracy.
* Splitting the dataset into training and testing subsets to validate the model’s generalization ability.

4.Optimization and Improvement:
* Additional testing with different hyperparameter configurations.
* Evaluating feature importance to enhance model interpretability.

### Project Conclusion

In this project, several machine learning algorithms were implemented for the regression task, with Random Forest emerging as the most effective model. However, to further improve the performance, additional tests with SVM (Support Vector Machine) could be conducted. Moreover, reducing features based on their importance and exploring different hyperparameter options would also be beneficial.

Work was not continued due to the long execution times of the scripts, limited by the available hardware capacity. In future projects, cloud computing will be utilized to improve execution times and optimize model performance.
