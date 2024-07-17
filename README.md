## Dataset:
[maildata](https://github.com/monikac24/OIB-SIP-Datasci-Spam_prediction/blob/main/mail_data.csv)
## Objective:
The objective of this project is to develop a machine learning model that can accurately classify emails as spam (0) or ham (1). This is achieved by using a logistic regression model trained on a labeled dataset of emails.

## Key Activities:
1. Data Collection and Preprocessing:
Loaded the dataset containing emails and their labels (spam or ham).
Replaced null values with empty strings.
Label encoded the categories: spam as 0 and ham as 1.

2. Data Splitting:
Separated the dataset into features (email text) and labels (spam/ham).
Split the data into training and testing sets.

3. Feature Extraction:
Transformed the email text data into numerical feature vectors using TF-IDF vectorization.

4. Model Training:
Trained a logistic regression model on the training data.

5. Model Evaluation:
Evaluated the model's performance on both training and testing datasets.

6. Building Predictive System:
Created a system to predict whether a new email is spam or ham based on the trained model.

## Technologies Used:
a) Libraries: pandas, numpy, sklearn (for model building and evaluation)

b) Techniques: TF-IDF Vectorization, Logistic Regression, Data Splitting, Accuracy Scoring

## Key Insights:
The accuracy of the model on both training and testing data indicates how well the model generalizes to unseen data.
TF-IDF Vectorization effectively transforms text data into numerical format suitable for machine learning models.
Logistic Regression is a simple yet effective model for binary classification problems such as spam detection.

## Conclusion:
This project successfully demonstrates how to build a spam detection system using machine learning. The logistic regression model, trained on TF-IDF features, is able to classify emails with a high degree of accuracy. This system can be further improved by exploring more advanced models or incorporating additional features.
