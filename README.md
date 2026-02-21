# Linear-Regresion-Revenue-Predicting

### GOAL:  Create a simple linear regression model and predicting the average customer purchase income (purchase_value, in monetary units) based on the time spent on the site (time_on_site, in minutes)

# Performing STEPS:

1. Build a scatter plot for the input data. Assess the type of dependence, draw the regression line on the graph.
2. Split the dataset into training and test data.
3. Train a linear model on the training data and make predictions for the test data.
4. Calculate MAE, MSE, RMSE, and  R2  to evaluate the prediction quality on the test dataset.
5. Calculate MAE, MSE, RMSE, and  R2  to evaluate the prediction quality using cross-validation.
6. Draw conclusions from the obtained metric values. Consider which metric is the most indicative in this task.

## Deliverables:
-Google Colab Notebook : https://colab.research.google.com/drive/1yo2NatXkBGU2kIG_j6Ltd0wWV9bPwjbE?usp=sharing#scrollTo=5pVSsPv5JOmA

## Google Colab Notebook Preview:
![# Scatterplot with regression line](https://github.com/OlexaKvitka/Linear-Regresion-Revenue-Predicting/blob/main/Linear-Regresion-Revenue-Predicting.PNG)

## Predict Revenue Summary

Predict Revenue SummaryThe metrics for the test set and cross-validation are remarkably close, indicating model stability, 
a lack of overfitting, and strong generalization capabilities.

**Model Performance:** Based on Linear Regression with 10-fold cross-validation (cv=10), the model achieved a Mean Absolute Error (MAE) of 46.45. 
This means the model's predictions deviate by an average of 46 monetary units.

**Error Analysis:** The RMSE ($56.1$) is only ~17% higher than the MAE. This relatively small gap suggests
there are no significant outliers in the data that would critically distort the forecast.

**Explanatory Power:* The $R^2$ value indicates that the model explains 84% of the target variable's variance.

**Key Metrics for Business Insights:**
- MAE: Provides a clear understanding of the average error in real-world units, making it the most practical metric for business logic.
- $R^2$ (Coefficient of Determination): Offers an intuitive percentage-based view of how well the input data explains the results.
