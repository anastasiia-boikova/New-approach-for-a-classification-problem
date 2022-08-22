# New-approach-for-a-classification-problem
The implementation of a new approach for classification problem. 
Data set from the Kaggle competition “Spaceship Titanic” (https://www.kaggle.com/competitions/spaceship-titanic)
The predictions are based on the” X_zero” value distribution across the rows in the data set which is presented in this algorithm.
The value “X_zero” for each row in a dataset is a value equal to the number of all features minus the value of each feature of a row. To calculate this value, all features must be scaled in [0, 1] interval (using the sklearn.preprocessing.MinMaxScaler, for example).The results indicates that the predictions based on the calculation of this simple value can have prediction accuracy comparable to some classical classification algorithms for a given dataset. 
