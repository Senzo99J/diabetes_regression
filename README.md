# The diabetes aims to predict a person's progression in the condition with respect to various attributes about them.

## Import and Install Libraries on Jupyter Notebook
* import pandas as pd
* from sklearn.Linear_Model import LinearRegression
* from sklearn.Preprocessing import MinMaxScaler, StandardScaler
* from slearn.Metrics import r2_score
* from slearn.Model_Selection import train_test_split

### Import the dataset and explore it
* Present the first five observation
* Differentiate between independent and dependent variables
* Assume the last column iss target variables
* Split the data into training and test sets(80% training, 20% test)
* Scale the data MinMaxScaler and StandardScaler
* Fit the scalers on the training data and transform both training and test data
* Generate a multiple linear regression model using training set
* Generate predictions for the test set
* Compute R-squared for the model on the set
  
