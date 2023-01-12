# Loan_Eligibility_Predition_usin-_Machine_Learning_Models-
Loan eligibility is simply the process of determining whether or not a potential borrower meets the criteria for a particular loan. This can be based on factors such as credit score, employment history, and income level. Loan eligibility is important because it helps to ensure that borrowers are able to repay their loans.Default can lead to a variety of negative consequences, including damage to one’s credit score and difficulty obtaining future financing.There are a variety of different methods and techniques that can be used to determine loan eligibility, and lenders will often use multiple methods in order to get a complete picture of the borrower. One common method is to pull a copy of the borrower’s credit report.To implement above methods, AI / machine learning and big data technologies can be used. The goal of this project:
* Analyze customer data provided in data set (EDA)
* Build various ML models that can predict loan approval
The machine learning models used in this project are:
Logistic Regression
K-Nearest Neighbour (KNN)
Support Vector Machine (SVM)
Naive Bayes
Decision Tree
Random Forest
Gradient Boost

### Data Source:
kaggle

### Data
For this problem, we have three CSV files: train, test.

* Train file will be used for training the model, i.e. our model will learn from this file. It contains all the independent variables and the target variable.
* Test file contains all the independent variables, but not the target variable. We will apply the model to predict the target variable for the test data.

### Data Set Description

There are 13 variables in this data set:

* 8 categorical variables,
* 4 continuous variables, and
* 1 variable to accommodate the loan ID.

#### Variable Name
* Loan_ID:	Loan reference number(unique ID)
* Gender:	Applicant gender(Male or Female)
* Married:	Applicant marital status(Married or not married)
* Dependents	Number of family members	0; 1; 2; 3+
* Education:	Applicant education/qualification(graduate or not graduate)	
* Self_Employed:	Applicant employment status(yes for self-employed, no for employed/others)	
* ApplicantIncome:	Applicant's monthly salary
* CoapplicantIncome:	Additional applicant's monthly salary
* LoanAmount:	Loan amount	
* Loan_Amount_Term:	The loan's repayment period (in days)
* Credit_History:	Records of previous credit history(0: bad credit history, 1: good credit history)	
* Property_Area:	The location of property(Rural/Semiurban/Urban)	
* Loan_Status:	Status of loan(Y: accepted, N: not accepted)
### Features
Now, let's visualize each variable separately. Different types of variables are Categorical, ordinal, and numerical.

* Categorical features: These features have categories (Gender, Married, Self_Employed, Credit_History, Loan_Status)
* Ordinal features: Variables in categorical features having some order involved (Dependents, Education, Property_Area)
* Numerical features: These features have numerical values (ApplicantIncome, Co-applicantIncome, LoanAmount, Loan_Amount_Term)

### Packages
Python
pandas
seaborn
sklearn
scipy
matplotlib
numpy
