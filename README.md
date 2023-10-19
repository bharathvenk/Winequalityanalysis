
# Wine Quality Prediction
This project involves predicting the quality of wine based on various physicochemical properties. The dataset used is the `winequality-white.
csv` file, which contains data on white variants of the Portuguese "Vinho Verde" wine. You can download the dataset from [this Google Drive 
link]
(https://drive.google.com/file/d/1b8qJrZJ36Qu4a7xSfhXG1ibbLmBIlF4h/view?usp=sharing)
.
## Models Used
Two models were used in this project: the Stochastic Gradient Descent (SGD) Regressor and the Ordinary Least Squares (OLS) model.
### Stochastic Gradient Descent (SGD) Regressor
The SGDRegressor model was used to predict the quality of the wine. The model was trained using a grid search to find the best combination of 
hyperparameters. The best hyperparameters found were:
- `alpha`
: 0.01
- `learning_rate`
: 'invscaling'
- `loss`
: 'huber'
- `penalty`
: 'l1'
The model was then evaluated on the test set. The test error, which is the mean squared error between the predicted and actual values on the 
test set, was found to be: <insert test error here>
The test accuracy, which is the coefficient of determination R^2 of the prediction, was: <insert test accuracy here>
The R-squared statistic, a statistical measure that represents the proportion of the variance for a dependent variable that is explained by an 
independent variable or variables in a regression model, was: <insert R-squared statistic here>
### Ordinary Least Squares (OLS)
The OLS regression model was used to predict the quality of the wine. The model was trained using the independent variables in the dataset. 
The summary of the model is: <insert model summary here>
The residuals of the OLS model were also analyzed. The residuals are the differences between the observed and predicted values of the 
dependent variable. The scatter plot of the residuals versus the actual quality and the histogram of the residuals are shown in the attached 
