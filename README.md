# customer-churn-prediction
## PROBLEM STATEMENT :
This project involves developing models that can predict which customers are likely to leave a company's service or products in the near future.
This prediction helps the businesses take a proactive measures to retain those customers, thus, reducing the churn and maintain a healthier customer base.
## WHY IS IT IMPORTANT TO SOLVE IT?
## 1. Business sustainability - high customer churn can be detrimental to a company's long term sustainability. A healthy customer base sustainability 
## supports the ongoing business growth.
## 2. customer relationship - Churn prediction indicates the customer dissatisfaction, so by addressing these issues business can improve their products, services.
## 3. data-driven strategies - It helps in data -driven decision making on the basis of the customer behaviour that helps in business progress.
## Now, before getting into solution of this problem lets collect insights from the dataset.
## 1. checking the null values
![image](https://github.com/sshreyaa05/customer-churn-prediction/assets/132264752/a9e3e571-8032-48d8-aeb4-bd1c677bb6cf)
## as we can see that there is no null values in the dataset.
## 2. plot of total count of churn vs not churn and show their percentage
![image](https://github.com/sshreyaa05/customer-churn-prediction/assets/132264752/df3079de-3eec-483a-82e7-747ee4379606)
![image](https://github.com/sshreyaa05/customer-churn-prediction/assets/132264752/6f1ffe27-7ad4-42c1-a3bd-0301cef143ed)
## so as we can see that the cases of not churn is more than those who have churned the comapny.
## 3. out of male and female who has churned more? showing their percentages as well.
![image](https://github.com/sshreyaa05/customer-churn-prediction/assets/132264752/bcb08e75-137f-41ab-81ac-fa1c47ba0dbe)
![image](https://github.com/sshreyaa05/customer-churn-prediction/assets/132264752/fc51050f-24cc-496b-8cdf-cb3cfb5861d5)
## so, the females have churned more as compared to males.
## 4. correlation plot
![image](https://github.com/sshreyaa05/customer-churn-prediction/assets/132264752/cd996c13-f106-41fc-8c36-a5df3fcc5633)
## as we can see that the payment delays are having strong positive correlation with the target variable which is churn,
## and the support calls and the tenure is also having a positive correlation with churn.
## 5. count plot showing the usage frequency of male vs female
![image](https://github.com/sshreyaa05/customer-churn-prediction/assets/132264752/e5efc827-cec0-4106-ae1d-9c9a241c9e0b)
## 6. Histogram showing the frequency distribution of support calls
![image](https://github.com/sshreyaa05/customer-churn-prediction/assets/132264752/0c2df241-8de2-42aa-a51a-bdfd15393af8)
## we can say that the support calls, in the interval of 9-10 has the highest frequency.
## NOW,TO SOLVE THIS PROBLEM WE NEED A ROBUST MODEL THAT GOING TO GIVE US THE ACCURATE SOLUTION, SO LETS GET STARTED WITH THE ENSEMBLE LEARNING 
## now, after the model training and tesing, we come up with the best evaluated model which is the xgboost classifier or the random forest classifier
## with the highest recall value of 1.00, thereby displaying the confusion matrix of both the models
## random forest classifier
![image](https://github.com/sshreyaa05/customer-churn-prediction/assets/132264752/909336a5-88c7-4991-a8f9-dbf8d76d16de)
## here, as we can see that the value of  false negative is 7
## xgboost classifier
![image](https://github.com/sshreyaa05/customer-churn-prediction/assets/132264752/82fd8cee-7d9c-4631-873d-fa9c1884b659)
## here the value of false negative is totally 0.
## as we compare the classification report of both the models we can see that both the models have recall score of 1.00, so we can also say that as the false negative value is 0 in case of xgboost classifier, hence is the best fitted model.
## hence, top 5 features are:
![image](https://github.com/sshreyaa05/customer-churn-prediction/assets/132264752/fe5b860e-aaa3-4a6e-bdc9-5b7cdeb6376e)
## payment delays
## support calls
## tenure
## usage frequency
## gender.

