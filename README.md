# House-Prices-Prediction
This project aims to predict the sale price of houses based on various features such as location, size, condition, amenities, etc. 
The project uses a dataset of 1460 house sales from the city of Ames, Iowa, USA. The dataset was obtained from Kaggle.

## Data Description
Dataset:-[House Price Prediction](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data?select=train.csv)
* The dataset contains 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. 
* The target variable is the sale price of the house in US dollars. 
* The dataset has been split into train and test sets, with 80% of the data in the train set and 20% in the test set.
  
## Data Exploration and Preprocessing
The data exploration and preprocessing steps include:
* Exploring the distribution and correlation of the target variable and the explanatory variables
* Handling missing values and outliers
* Encoding categorical variables
* Transforming skewed variables
* Scaling numerical variables
* Creating new features from existing ones

## Model Building and Evaluation
The model building and evaluation steps include:
* Splitting the train set into train and validation sets.
* Applying various regression models such as Multiple linear regression, random forest regression, gradient boosting regression, decision tree regressor, etc.
* Tuning the hyperparameters of the models using grid search or random search
* Comparing the performance of the models using root mean squared error (RMSE) as the evaluation metric
