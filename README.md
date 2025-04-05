# Housing Price Prediction

This repository contains a predictive model to forecast housing prices based on various features such as location, size, and age. The model is built using Python and scikit-learn.

## Dataset

The dataset used in this project is the Boston housing dataset, which includes the following features:
- CRIM: per capita crime rate by town
- ZN: proportion of residential land zoned for lots over 25,000 sq. ft.
- INDUS: proportion of non-retail business acres per town
- CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- NOX: nitric oxides concentration (parts per 10 million)
- RM: average number of rooms per dwelling
- AGE: proportion of owner-occupied units built prior to 1940
- DIS: weighted distances to five Boston employment centers
- RAD: index of accessibility to radial highways
- TAX: full-value property tax rate per $10,000
- PTRATIO: pupil-teacher ratio by town
- B: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town
- LSTAT: percentage of lower status of the population
- MEDV: median value of owner-occupied homes in $1000s

## Model

The model used in this project is a linear regression model. The steps involved in building the model are:
1. Data loading and preprocessing
2. Splitting the data into training and testing sets
3. Training the linear regression model
4. Making predictions on the test set
5. Evaluating the model using Mean Squared Error (MSE)

## Results

The Mean Squared Error (MSE) of the model on the test set is **24.29**.

## How to Use

1. Clone the repository:
   ```bash
   
cd housing-price-prediction
Install the required libraries:
pip install -r requirements.txt
Run the Jupyter Notebook:
jupyter notebook
