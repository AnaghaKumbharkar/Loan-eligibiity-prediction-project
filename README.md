# Loan-eligibiity-prediction-project
In this project predictive model is built to automate the process of targeting right applicants. Algorithms used to build predictive model are Logistic Regression, Decision tree, Random forest, kNN, SVM.
**Problem Statement** 
The Bank deals in all kinds of home loans. They have a presence across all urban, semi-urban and rural areas. The customer first applies for a home loan and after that, the company validates the customer eligibility for the loan.The bank wants to automate the loan eligibility process based on customer details. These details are Loan ID, Gender, Marital Status, Education, number of Dependents, Income, Loan Amount, Credit History, and others.To automate this process, they have provided a dataset to identify the customer that are eligible for loan so that they can specifically target these customers.
**Understanding The Data**
There are 614 observations with 13 fields in our dataset.
Target label is Loan status (Binary categorical variable).
Categorical variables(9):Gender (Male/Female),Married(Yes/No),Number of dependents (Possible values:0,1,2,3+)(Ordinal),Education (Graduate / Not Graduate),Self-Employed(Yes/No),credit history(Yes/No),Property Area (Rural/Semi-Urban/Urban)(Ordinal),Loan Status(Yes/No)(i.e.Target variable),Tenure.
Continuous/Numerical variables(4):Loan ID,Applicant Income,Co-applicant Income,Loan Amount.
