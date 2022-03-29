
## Goal:
To predict the Saleprice prices for each house.

## Data exploration:
1.training data set has 1460 samples, 80 features,1 target variable.

2.test data has 1459 samples, 80 features.

3.the target variable is SalePrice.
## Feature engineering:
1.the test dataset set and train dataset has same columns with uneven categories, therefore Concatenate both the datasets.

2.Checking for missing values.
![download](https://user-images.githubusercontent.com/96624753/160601208-145026f8-169e-4d30-bce5-a48204ef921f.png)
3.dropping columnswith greater 70 percent missing values

4.the dataset has 37 numerical columns and 38 categorical columns.

5.filling missing values of numerical colums with mean. and categorical with most frequent element.

6.the target variable is right skewed.

7.Checking corelation of indepent featrues with target variable.

8.dropping the features which are having low corelation with target variable.
## Feature scaling:
Normalization. scaling down the values using minmax scalar as the data does not follow noraml distribution.
## Independent and dependent variables:

1.Creating independent and dependent variables.

2.Splitting the dataset into the Training set and Test set.
## Training the model:
1.Fitting the training data.

2.Applying linear regression model on data.

3.predicting the traget variable.


## Result:

1.The linear regreesion model got the r2_score of 87.80%