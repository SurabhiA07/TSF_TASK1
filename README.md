# Students data Analysis
# Prediction-Using-Supervised-ML
# Students Data Analysis 
# Created by- Surabhi Awate © 2024
## Social Media's--> LinkedIn: @awatesurabhi  | GitHub: @SurabhiA07

## INDEX
- Aim
- Description
- Method used
- conclusion
## Aim
This project aims to build a linear regression model to predict student scores based on the number of study hours, evaluate its performance, and visualize the relationship between study hours and scores.
## Description
- The dataset consist of two columns: 'Hours' representing the number of study hours, and 'score' representing the corresponding scores achieved by student.
- the data is structured into dataframe using pandas library. it splits data into training and testing sets using train_split method.
- Utilizes LinearRegrassion model from scikit-learn to fit the training data and make predictions.
- visualizes the predicted scores against the actual scores for testing set using matplotlib
- lastly, it plots the regression line along with the training and testing data points.
## Requirements
- Python Environment
- Libraries like numpy, scikit-learn and pandas.
## Conclusion
- Predicted Score for 9.25 Hours of Study: According to the trained linear regression model, the predicted score for a student studying 9.25 hours per day is approximately 92.91.
- Model Evaluation: To further evaluate the model's performance, you would typically assess metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), or Root Mean Squared Error (RMSE) on the test set. These metrics provide insights into how well the model generalizes to unseen data. Additionally, visualizing the actual vs. predicted scores on a scatter plot could provide a qualitative assessment of the model's performance.
- Predicted Scores for Test Set: The model also predicts scores for the test set, which represents unseen data. These predictions are made based on the linear relationship learned during the training phase. The predicted scores for the test set are listed above.
