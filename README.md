# Vehicle-Loan-Repayment-Prediction-Model
This is a Machine Learning project which is basically a classification model for loan default risk prediction.

In real world, a loan in time enables the borrower to meet financial goals. At the same time, the interest associated with the loan generates revenues for the lender.
However, there is always a risk associated with lending, especially in case of customers having insufficient or non-existent credit histories. If the borrower defaults a loan, then that loan becomes non-performing asset (or, NPA) for the lender. Any NPA hits the bottom-line of the lending organization.

Therefore, every lending organization strives to assess the risk associated with the loan. Primarily, they want to assess their clients’ repayment abilities well in advance before deciding on approval and disbursement of loans.

The objective is to predict whether a client is likely to default on their vehicle loan payment or not. The task involves building a model using the Train_Dataset and testing the model on the Test_Dataset which i  got from kaggle which is basically provided by A non-banking financial institution (NBFI) or non-bank financial company (NBFC).

The Workflow of this Project is like this:


1.First step is to understand the data ,understand about the classification ,different values in the dataset.



2.Second Step is Little bit pre-processing to use this data

    Following steps have been performed on the data
    
    1.Handling missing values by replacing null values and filling them with statistical methods.
    
    2.Handling outliers by removing outliers from dataset.
    
    3.Encoding categorical variables by with the help of categorical mapping.
    
    4.Feature scaling with the help of standard scaler.
    
3.Third step is selection of evaluation metrics .For classification of loan default risk, I choosed Area under receiver operating characteristic curve(AUC-ROC).


4.Next step is selection of model ,in this case i selected model with highest AUC-ROC value which is 0.73 and the model is Random Forest with Oversampling.


AUC represents degree or measure of separability. Higher the AUC, better the model is at predicting 0s as 0s and 1s as 1s.

When AUC is 0.7, it means there is 70% chance that model will be able to distinguish between positive class and negative class. 

This means, our model will be correct on 70% times in identifying a borrower having risk of defaulting a loan.


5.Last step is to use the trained model to do prediction  on test dataset in which i got 60 clients with certain client who are going to get default on vehicle loan repayment.

Conclusion -
1.Data is Highly imbalanced because of this the evaluation becomes difficult.

2.Cleaning should be done properly otherwise model will lose some important data.

3.Use hyperparameters to tune  your model to get better values.

Linkedin Video Post Link:-https://www.linkedin.com/posts/kaushik-kathwal-372769290_machinelearning-datascience-dataengineering-activity-7183530932870475776-lHKW?utm_source=share&utm_medium=member_desktop


