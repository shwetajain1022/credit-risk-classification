#Credit risk classification
------------------------------
##Overview of the Analysis
-----------------------

Following CSV fields are available :
--------------------------
loan_size \
interest_rate \
borrower_income \
debt_to_income \
num_of_accounts \
derogatory_marks \
total_debt \
loan_status \

A dataset with 77,536 rows is split into training and testing sets. The training data set is applied to logistic regression model. The purpose of the model is to evaluate whether a loan in the testing set is a low- or high-risk and results are summarized below.  \
We can see that the logistic regression model does not suffice to the prediction as it had 75,036 low-risk loan data points and 2,500 high-risk data points. So, This needed to use imbalance-learn library. For this,We had resampled the training data using RandomOverSampler module from imbalanced-learn.  \

##Results
---------------------------
1. Logistic Regression Modelling Results \

Accuracy Score \
![image](https://user-images.githubusercontent.com/40103518/237030735-56f9ab80-e2f4-45d0-83d5-d4ae670bd542.png)

Classification Report \
![image](https://user-images.githubusercontent.com/40103518/237030932-7ee37055-4951-448a-85cf-1fe2a2ecc719.png)

2. Random Over Sampler Modelling Results \

Accuracy Score \
![image](https://user-images.githubusercontent.com/40103518/237031319-288f56f7-9523-4f79-9b05-9a582fc5f729.png)

Imbalanced Classifictaion Report \
![image](https://user-images.githubusercontent.com/40103518/237031399-7a67388b-978e-44b0-9693-59e75fa3ba78.png)

Summary
-------------------------------
![image](https://user-images.githubusercontent.com/40103518/237032341-6f6b2eac-d381-4b24-a24f-57a953f65f22.png)

![image](https://user-images.githubusercontent.com/40103518/237032272-df275eea-ac5d-49fc-9aaa-acf9cf9284ef.png)

