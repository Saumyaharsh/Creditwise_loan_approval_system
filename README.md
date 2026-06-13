**CreditWise Loan System**
Problem Statement
A mid-sized financial company named SecureTrust Bank offers personal and home loans to customers across urban and rural regions of India. Every day, hundreds of customers apply for loans through online and branch applications.
Until now, SecureTrust Bank has been using a manual verification process where loan officers evaluate applications by checking income proofs, employment details, credit history, and other documents. This process is time-consuming, biased & inconsistent.
As a result, the bank faces two major challenges:
1.	Good customers sometimes get rejected, leading to loss of business.
2.	High-risk customers sometimes get approved, leading to financial losses.
Dataset Description
Each row in the dataset represents a loan applicant and contains multiple attributes describing their personal, financial, and credit information.
Column	Description
Applicant_ID	Unique applicant ID
Applicant_Income	Monthly income of applicant
Coapplicant_Income	Monthly income of co-applicant
Employment_Status	Salaried / Self-Employed / Business
Age	Applicant age
Marital_Status	Married / Single
Dependents	Number of dependents
Credit_Score	Credit bureau score
Existing_Loans	Number of already running loans
DTI_Ratio	Debt-to-Income ratio
Savings	Savings balance
Collateral_Value	Value of collateral provided
Loan_Amount	Loan amount requested
Loan_Term	Loan duration (months)
Loan_Purpose	Home / Education / Personal / Business
Property_Area	Urban / Semi-Urban / Rural
Education_Level	Graduate / Postgraduate / Undergraduate
Gender	Male / Female
Employer_Category	Govt / Private / Self

To solve this problem I have made a ML project using following steps
1. Handling Missing or Null values
2. Exploratory Data Analysis using bar graph and pie chart for categorical variables and histogram for numerical variables also used boxplot to detect outliers
3. Scaling of data is done and feature encoding is done
4. Then I used Logistic Regression, Naive Bayes and KNN algorithm for binary classification.Since we have to increase precision and recall so Naive Bayes performs better than Logistic and KNN model for this dataset
5. After that I did feature engineering where Logistic Regression model gives better result than other two models.
Loan_Approved (Target)	1 = Approved, 0 = Rejected

