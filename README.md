# deep-learning-challenge

# Fundraising Success Prediction

This project focuses on predicting the fundraising success of nonprofit organizations using a machine learning model. The goal is to develop a model that can accurately classify whether a fundraising campaign will be successful or not.

## Dataset

The dataset used for this project is contained in the `application_df.csv` file. It includes various features such as application type, affiliation, classification, use case, organization, income amount, special considerations, and the target variable indicating whether the fundraising campaign was successful or not. The analysis involves data preprocessing, model compilation, training, and evaluation.

## Data Preprocessing
Target variable: The target variable for the model is the "IS_SUCCESSFUL" column, which indicates whether a fundraising campaign was successful or not.
Feature variable: All columns in the dataset except for the target variable are considered as features for the model.
Variables to be removed: The "EIN" and "NAME" columns, which serve as non-beneficial ID columns, are removed from the input data as they do not contribute to the model's predictive power.

## Results

The model was evaluated using the test data, and the results are as follows:

Loss: 0.5554785132408142
Accuracy: 0.7261807322502136

The model achieved an accuracy of approximately 72.62% on the test data, which means it correctly classified around 72.62% of the fundraising campaigns as either successful or not. The loss value of 0.5555 indicates that the model's predictions have a relatively low error rate.

