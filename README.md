## Thera Bank Personal Loan Campaign
**Data Description:**

The dataset contains data on 5000 customers. The data include customer demographic information (age, income, etc.), the customer's relationship with the bank (mortgage, securities account, etc.), and the customer response to the last personal loan campaign (Personal Loan). Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign.

**Domain:**

Banking

**Context:**

This case is about a bank (Thera Bank) whose management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors). A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio with a minimal budget.
Attribute Information:

- **ID**: Customer ID
- **Age**: Customer's age in completed years
- **Experience**: #years of professional experience
- **Income**: Annual income of the customer ($000)
- **ZIP Code**: Home Address ZIP code.
- **Family**: Family size of the customer
- **CCAvg**: Avg. spending on credit cards per month ($000)
- **Education**: Education Level. 1: Undergrad; 2: Graduate; 3: Advanced/Professional
- **Mortgage**: Value of house mortgage if any. ($000)
- **Personal Loan**: Did this customer accept the personal loan offered in the last campaign?
- **Securities Account**: Does the customer have a securities account with the bank?
- **CD Account**: Does the customer have a certificate of deposit (CD) account with the bank?
- **Online**: Does the customer use internet banking facilities?
- **Credit card**: Does the customer use a credit card issued by the bank?

**Learning Outcomes:**
- Exploratory Data Analysis
- Preparing the data to train a model
- Training and making predictions using a classification model
- Model evaluation

**Objective:**

The classification goal is to predict the likelihood of a liability customer buying personal loans.
Steps and tasks:
1. Import the datasets and libraries, check datatype, statistical summary, shape, null values or incorrect imputation. (5 marks)
2. EDA: Study the data distribution in each attribute and target variable, share your findings (20 marks)
- Number of unique in each column?
- Number of people with zero mortgage?
- Number of people with zero credit card spending per month?
- Value counts of all categorical columns.
- Univariate and Bivariate
- Get data model ready
3. Split the data into training and test set in the ratio of 70:30 respectively (5 marks)
4. Use Logistic Regression model to predict whether the customer will take personal loan or not. Print all the metrics related for evaluating the model performance (15 marks)
5. Check different parameters of Logistic Regression and give your reasoning whether the model performance is affected due to it or not? (10 marks)
6. Give Business understanding of your model? (5 marks)
