## Sales Prediction using Python
![intro_img](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/Oasis_data_science_Intern_Task_5_Sales_Prediction_using_Python.png)

## Features -> TV, Radio, Newspaper
## Target -> Sales

![demo](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/demo.jpg)

[.csv file of the cleaned dataset](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/advertising_cleaned.csv)

## Correaltion Plot of each features with target(sales)
![corr_plot](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/correlation%20plot.png)
### From the above correlation plot we have feature: -
### 'TV' having an impact score of 0.78 on Sales
### 'Radio' having an impact score of 0.58 on Sales
### 'Newspaper' having an impact score of 0.23 on Sales

## Plotly Scatterplots of features vs target
### (A) Scatter Plot of TV(Feature) vs Sales(Target)
![img_a](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/scatter%20plot%20sales%20vs%20tv.png)
#### From the above scatterplot we can infer that
#### As the score of TV is increasing score of Sales is also increasing

### (B) Plotly Scatterplot of Radio(feature) vs Sales(Target)
![img_b](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/scatter%20plot%20sales%20vs%20radio.png)
#### From the above scatterplot we can infer that
#### As the score of Radio is increasing score of Sales is also increasing

### (C) Plotly Scatterplot of Newspaper(feature) vs Sales(Target)
![img_c](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/scatter%20plot%20sales%20vs%20newspaper.png)


## Histogram Distribution of each features and target
### (A) Distribution of TV feature
![img_A](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/distribution%20hist%20plot%20tv.png)
### (B) Distribution of Radio feature
![img_B](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/distribution%20hist%20plot%20radio.png)
### (C) Distribution of Newspaper feature
![img_C](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/distribution%20hist%20plot%20newspaper.png)
### (D) Distribution of Sales
![img_D](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/distribution%20hist%20plot%20sales.png)


## Predicted vs Actual Sales value plots of each Regression Model
### (A) Linear Regression Model
### R^2 score : 0.8859649783578775
![img_a](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/pred%20linear%20regression.png)

### (B) Random Forest Regression Model
### R^2 score : 0.9692326073896234
![img_b](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/pred%20random%20forest%20regression.png)

### (C) Ridge Regression Model
### R^2 score : 0.885965692374097
![img_c](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/pred%20ridge%20regression.png)

### (D) Lasso Regression Model
### R^2 score : 0.8873432660828356
![img_d](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/pred%20lasso%20regression.png)

### (E) ElasticNet Regression Model
### R^2 score : 0.8867449612862289
![img_e](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/pred%20elasticnet%20regression.png)

### (F) Gradient Boosting Regression Model
### R^2 score : 0.9759214404300837
![img_f](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/pred%20gradient%20boosting%20regression.png)

### (G) XGBoost Regression Model
### R^2 score : 0.9736706437287413
![img_g](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/pred%20xgboost%20regression.png)


## Features Impact on the Sales (as predicted by the best performing model: Gradient Boosting Regression Model having R^2 Score 0.9759)
![img_impact](https://github.com/ADVAIT135/OIBSIP/blob/8313fda91650766a7060f06109ada1e14605a1ad/Task%205%3A%20Sales%20Prediction%20using%20Python/feature%20impact%20on%20sales.png)
### From the above plot we have: -
### Advertising Platform TV having an impact of 64% on Sales
### Advertising Platform Radio having an impact of 36% on Sales


