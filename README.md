# Finance-Project-Financial-Inclusion-in-East-Africa

## Project Overview

The Project focused on 4 East African countries i.e Kenya, Rwanda, Tanzania and Uganda. The main objective of this project was to predict whether an individual from either of the countries have a bank account or not, using sociodemographic and economic factors such as cellphone access, location type, marital status, education level, age of respondent etc. as main predictors.

## Data Preprocessing

Data Preprocessing was performed to check sanity of data e.g. missing values, duplicates, data types etc., EDA was also analyzed to undertand the structure and distribution of the data, bar plots through cross-tabulation were mainly used as most of the variables were categorical.

## Variable definition and splitting the data

The definition of the variables was done to specify the outcome and predictor variables. Splitting the data into training and testing sets followed.

## Pipeline creation

A preprocessing pipeline was created using column transformer to hanle mixed data types where numerical columns were scaled using standard scaler function and categorical columns were encoded using Onehot encoder function.

## Model deployment
A model fitting pipeline was also created where a Logistic regression model and a Random Forest Classifier were fitted to the data. Logistic regression recorded a higher accuracy score of 88% than the Random forest Classifier which recorded an accuracy of 86%. This indicated some consistency in how the models performed.

The best model was deployed using Gradio where the model pipeline was loaded, the prediction function created and lastly a demo.


