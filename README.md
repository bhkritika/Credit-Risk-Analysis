# CREDIT RISK ANALYSIS

An advanced credit risk analysis project using machine learning models to predict credit default.
## OBJECTIVE

The main objective of this project is to develop a robust machine learning model for credit risk analysis that can effectively predict the likelihood of credit default based on various features such as borrower's demographic information, financial history, and loan attributes. By utilizing a diverse set of classification algorithms and advanced data preprocessing techniques, this project aims to achieve high accuracy and precision in identifying potential credit risks, thus assisting financial institutions in making informed lending decisions and minimizing default losses.


## INTRODUCTION

Credit risk analysis plays a crucial role in the lending process for financial institutions. It involves assessing the creditworthiness of borrowers to determine the likelihood of default on loans. With the advancement of machine learning techniques, predictive models can be trained on historical data to automate this process and provide valuable insights into potential risks associated with lending.

This Credit Risk Analysis project leverages various machine learning algorithms to analyze a dataset containing information about borrowers and their loan applications. The project focuses on building robust classification models capable of accurately predicting credit default. By utilizing state-of-the-art machine learning libraries and techniques, this project aims to provide a comprehensive solution for credit risk assessment, assisting financial institutions in making data-driven lending decisions.


## DATASET 

The dataset used in this project contains a comprehensive set of features related to borrowers and their loan applications. The features include demographic information, financial attributes, loan details, and credit history. The target variable indicates whether the loan was repaid on time (0) or defaulted (1).

## Features 

1. person_age: Age of the borrower.
2. person_income: Annual income of the borrower.
3. person_home_ownership: Type of home ownership (e.g., rent, mortgage, own).
4. person_emp_length: Employment length in years.
5. loan_intent: Purpose of the loan (e.g., education, medical, venture).
6. loan_grade: Loan grade assigned by the lender.
7. loan_amnt: Loan amount requested.
8. loan_int_rate: Interest rate on the loan.
9. loan_status: Loan status (0: Repaid on time, 1: Defaulted).
10. loan_percent_income: Percentage of income dedicated to servicing the loan.
11. cb_person_default_on_file: Historical default status of the borrower.
12. cb_person_cred_hist_length: Length of the credit history in years.

## MODELS

The project utilizes the following machine learning models for credit risk analysis:

1. Gaussian Naive Bayes (GNB)
2. Decision Tree
3. Random Forest
4. Logistic Regression
5. AdaBoost
6. XGBoost
7. LightGBM
8. K-Nearest Neighbors (KNN)
## CONCLUSION

1. GaussianNB
This model had an accuracy of around 82.17%. Although it has reasonable precision and recall, its F1-score is slightly lower compared to other more complex models.

2. DecisionTreeClassifier
With an accuracy of around 89%, this model seems to be a good choice. Its F1-score is also high, indicating a good balance between precision and recall.

3. KNeighborsClassifier
With an accuracy of about 87.26%, this model is also reasonably good. However, its F1-score is a little lower compared to DecisionTreeClassifier.

4. RandomForestClassifier
With an accuracy of around 93%, this model stands out as one of the best. It demonstrates a high F1-score, indicating good overall performance.

5. LogisticRegression
With an accuracy of around 80%, this model appears to be in an intermediate position in terms of performance. Its F1-score is a little lower compared to other models.

6. AdaBoostClassifier
With an accuracy of around 88.11%, this model is a solid performer. Its F1-score is also relatively high.

7. XGBClassifier
With an accuracy of around 93.47%, this model is one of the best in terms of performance. It demonstrates a very high F1-score, indicating excellent classification ability.

8. LGBMClassifier
With an accuracy of around 93.59%, this model is also one of the best. It demonstrates a very high F1-score, just like
## Acknowledgements

 - [Providing the machine learning library](https://scikit-learn.org/stable/)
 - [Providing the GPT-3 model used to generate this README template.](https://openai.com/)


