## Car Price Prediciton using Machine Learning
![Intro](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/Oasis_data_science_Intern_Task_3_Car_Price_Prediction_using_Machine_Learning.png)

## Features -> Year, Transmission Type, Fuel Type, Present Price, Ownership Type, Driven Kilometers, Selling Type
## Targets -> Selling Price
![demo](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/Car%20Price%20Predcitions.png)


### .csv file of the cleaned dataset(removed duplicates)
[cleaned_data.csv](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/car_data_cleaned.csv)

## 1. Discrete Categorical Features vs Number of Cars Sold 
### A. Year vs Number of Cars sold
![img_1](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/Year%20vs%20no%20of%20cars.png)

### B. Transmission Type vs Number of cars sold
![img_2](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/transmission%20type%20vs%20no%20of%20cars%20sold.png)

### C. Fuel Type vs Number of Cars sold
![img_3](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/fuel%20type%20vs%20no%20cars%20sold.png)

### D. Ownership Type vs Number of Cars Sold
![img_4](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/ownership%20vs%20no%20of%20cars%20sold.png)

### E. Selling Type vs Number of cars sold
![img_5](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/selling%20type%20vs%20no%20cars%20sold.png)

### F. Top 25 Car Name vs number of cars sold
![img_5a](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/Top%2025%20car%20name%20vs%20no%20of%20cars%20sold.png)

## 2. Continuous Features
### A. Distribution of Selling Price 
![img_6](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/dist%20hist%20selling%20prices.png)

### B. Distribution of Present Price
![img_7](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/dist%20hist%20present%20price.png)

### C. Distribution of Driven Kilometers
![img_8](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/dist%20hist%20driven%20kms.png)

### .csv file for encoded data of the cleaned dataset
[cars_cleaned_encoded.csv](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/cars%20price%20encoded.csv)

## 3. Discrete Categorical Features(encoded) vs Number of Cars Sold
### A. Transmission Type(encoded) vs Number of Cars sold
![img_9](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/transmission%20type%20encoded%20vs%20no%20cars%20sold.png)

### B. Fuel Type(encoded) vs Number of Cars sold
![img_10](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/fuel%20type%20encoded%20vs%20no%20of%20cars%20sold.png)

### C. Ownership Type(encoded) vs Number of cars sold
![img_11](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/ownership%20encoded%20vs%20no%20of%20cars%20sold.png)

### D. Selling Type(encoded) vs Number of cars sold
![img_12](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/selling%20type%20encoded%20vs%20no%20of%20cars%20sold.png)

## 4. Correlation Plot of the features of the encoded dataset
![img_13](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/correaltion%20plot.png)

## 5. Training using the given Machine Leanring Models and their outcome(R^2) Scores:-
### A. Linear Regression Model:
### R^2 Score : 0.838
![img_14](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/pred%20linear%20regression.png)

### B. Random Forest Regression Model:
### R^2 Score : 0.699
![img_15](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/pred%20randomforestregression.png)

### C. Ridge Regression Model:
### R^2 Score : 0.8401
![img_16](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/pred%20ridge%20regression.png)

### D. Lasso Regression Model:
### R^2 Score : 0.819
![img_17](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/pred%20lasso%20regression.png)

### E. ElasticNet Model:
### R^2 Score : 0.8258
![img_18](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/pred%20elasticnet%20regression.png)

### F. Gradient Boosting Regression Model:
### R^2 Score : 0.8741
![img_19](https://github.com/ADVAIT135/OIBSIP/blob/48da506aa34881f96d98eb6c5ad8fa67b0f48654/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/pred%20gradientboosting.png)

### G. XGBoost Regression Model:
### R^2 Score : 0.9031
![img_20](https://github.com/ADVAIT135/OIBSIP/blob/9a6870b4bf6f43e3f84dd22a4643e39f0f8a9c7e/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/pred%20xgboost%20regression.png)


## 6. Selecting Final Model as XGBoost Regression Model and the finding the important fetaures that influence the selling price of the car
### XGBoost Regression Model
### R^2 Score : 0.9031
![img_21](https://github.com/ADVAIT135/OIBSIP/blob/336892fc47eaf0afe77dcbe7b6c71d6c58296aba/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/pred%20final.png)

### Important Features
![img_22](https://github.com/ADVAIT135/OIBSIP/blob/336892fc47eaf0afe77dcbe7b6c71d6c58296aba/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/pred%20imp%20features%20using%20final%20model.png)


## 7. Trivariate Analysis of Selling_Price, Present_price vs Year
![img_23](https://github.com/ADVAIT135/OIBSIP/blob/336892fc47eaf0afe77dcbe7b6c71d6c58296aba/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/plot%20of%20selling%20price%2C%20present%20price%20vs%20year.png)

## 8. Bivariate Analysis of Selling_price vs Year
![img_24](https://github.com/ADVAIT135/OIBSIP/blob/336892fc47eaf0afe77dcbe7b6c71d6c58296aba/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/plot%20of%20selling%20price%20vs%20year.png)

## 9. Bivariate Analysis of Present Price vs Year
![img_25](https://github.com/ADVAIT135/OIBSIP/blob/336892fc47eaf0afe77dcbe7b6c71d6c58296aba/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/plot%20of%20present%20price%20vs%20year.png)

### .h5 file of the final model (XGBoost Regression Model)
[final_model.h5](https://github.com/ADVAIT135/OIBSIP/blob/336892fc47eaf0afe77dcbe7b6c71d6c58296aba/Task%203%3A%20Car%20Price%20Prediction%20using%20Machine%20Learning/final_car_prediction_model.h5)

