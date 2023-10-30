## Email Spam Detection using Machine Learning
![Intro](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/Oasis_data_science_Intern_Task_4_Email_Spam_Detection_Using_Machine_Learning.png)

## Features -> Text Message
## Target -> Ham(Non-spam) or Spam Message

![demo](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/demo.jpg)

[.csv of the cleaned dataset](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/spam_cleaned.csv)

## Categorical Count of each Message
## Ham(Non-Spam) and Spam vs count of message
![img_a](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/class%20vs%20count.png)

## Highest common text message that occurred in the dataset
![img_b](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/most%20common%20string.png)

[.csv of the encoded dataset](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/spam_encoded_cleaned.csv)

## Training dataset with Classification Models
### [A] Multinominal Naive Bayes Classifier: -
### Accuracy_score = 0.9856459330143541
### Average Precision score = 0.91
![img_c](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/confusion%20matrix%20MultinomialNB.png)
### Multinomial Naive Bayes Classifier correctly predicts 1424 samples as Actual Ham (Non-spam) messages and 224 samples as Spam messages
![img_d](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/Precision%20Recall%20Curve%20MultinomialNB.png)

### [B] Logistic Regression Classifier
### Accuracy_score = 0.9802631578947368
### Average Precision score = 0.88
![img_e](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/confusion%20matrix%20Logistic%20Regressor.png)
### Logistic Regression Classifier correctly predicts 1429 samples as Actual Ham (Non-spam) messages and 210 samples as Spam messages
![img_f](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/Precision%20Recall%20Curve%20Logistic%20Regressor.png)

### [C] Decision Tree Classifier
### Accuracy_score = 0.965311004784689
### Average Precision score = 0.79
![img_g](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/confusion%20matrix%20Decision%20Tree%20Classifier.png)
### Decision Tree Classifier correctly predicts 1409 samples as Actual Ham (Non-spam) messages and 205 samples as Spam messages
![img_h](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/Precision%20Recall%20Curve%20Decision%20Tree%20Classifier.png)

### [D] Random Forest Classifier
### Accuracy_score = 0.972488038277512
### Average Precision score = 0.84
![img_i](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/confusion%20matrix%20Random%20Forest%20Classifier.png)
### Random Forest Classifier correctly predicts 1428 samples as Actual Ham (Non-spam) messages and 198 samples as Spam messages
![img_j](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/Precision%20Recall%20Curve%20Random%20Forest%20Classifier.png)

### [E] Support Vector Machine Classifier
### Accuracy_score = 0.9742822966507177
### Average Precision score = 0.85
![img_k](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/confusion%20matrix%20SVM%20Classifier.png)
###  Support Vectore Machine Classifier correctly predicts 1429 samples as Actual Ham (Non-spam) messages and 200 samples as Spam messages
![img_l](https://github.com/ADVAIT135/OIBSIP/blob/e8fd19fc0cb10254c75cdc772077180c09871241/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/Precision%20Recall%20Curve%20SVM%20Classifier.png)


## Saving the best performing Model i.e. Multinomial Naive Bayes Classifier having accuracy_score =  0.9856459330143541 and Average Precision score = 0.91
[.joblib file of the trained and tested model](https://github.com/ADVAIT135/OIBSIP/blob/4260bca1acf6e16a68c4b4ece2512fc9d39d7b2a/Task%204%20%3A%20Email%20Spam%20Detection%20Model%20using%20Machine%20Learning/multinomial_nb_model.joblib)
