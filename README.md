# Machine-Learning- Titanic Ship
Titanic Assignment

A data science enthusiast came up with one of the famous legendary Titanic ship dataset to find the passengers who survived the Titanic shipwreck with the help of machine learning models,.

# Problem

In this capstone project, you need to dive into a dataset to analyze the given description attributes for target variables with the help of data Preprocessing, Exploratory data analysis to investigations on data so as to discover patterns, statistics and graphical representations to process next step towards Feature Engineering for features selection to apply Machine Learning models.

# Dataset

The Titanic's sinking is one of history's most famous shipwrecks. The "unsinkable" RMS Titanic sank on April 15, 1912, during her maiden voyage, after striking with an iceberg. Unfortunately, there were insufficient lifeboats to accommodate everyone onboard, resulting in the deaths of 1502 of the 2224 passengers and crew. 

The dataset contains 7 columns and 1313 rows, attributes are:

Unnamed: Unnamed column contains unique values likes 1,2,3, and so on.
Name: Name column contains names of the passengers.
PClass: Passenger classes like 1st, 2nd, and 3rd.
Age: Age of the passenger.
Sex: Gender of the passenger.
Survived: Survived column contains 0 and 1 values 0 is unsurvived, 1 is survived.
SexCode: SexCode contains 0 and 1 values 0 is female, 1 is male.
Performance Evaluation
The performance evaluation matrix is based on the following:
Importing necessary Libraries, and data preparation. 
Data validation, Statistical analysis, data overview, Data types.
Data manipulation/Data pre-processing, EDA.
Building model(choose appropriate algorithm), Model training, Model evaluation.
Parameter tuning, Model accuracy, visualizing results, Execution/Results.    
Requirements or Deliverables
Read the Titanic dataset and import all required libraries.
Find out in the target column (survival) what is the respective count of values.
Confirm through a chart that Women are more likely to survive than Men.
Confirm through a chart that a person boarded with more than 2 siblings or spouse is more likely to survive.
Write code to convert categorical columns to equivalent dummy variables.
Perform predictions on the Test dataset.
Create the confusion matrix.
Find the accuracy of your model.                
Bank Term Deposit Opening Decision 
The Portuguese bank Institution's aim is to promote term deposits among existing customers, so they conduct a campaign from 2008 to November 2010. The marketing campaigns were based on phone calls. Often, more than one contact with the same client was required, in order to assess if the product (bank term deposit) would be ('yes') or not ('no') subscribed by the client.
Problem
In this capstone project, you need to use the direct marketing campaign data of a Portuguese banking institution. The goal is to predict if the client will subscribe to a term product (variable Y).

# Dataset

The data is related to direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to (1/0) to a term deposit (variable y).
This dataset provides the customer information. It includes 41188 records and 21 fields.
age (numeric)
 job : type of job (categorical: 'admin.', 'blue-collar', 'entrepreneur', 'housemaid', 'management', 'retired', 'self-employed', 'services', 'student', 'technician', 'unemployed', 'unknown')
 marital : marital status (categorical: 'divorced','married','single','unknown'; note:'divorced' means divorced or widowed)
education (categorical:'basic.4y', 'basic.6y', 'basic.9y', 'high.school', 'illiterate', ‘professional.course', 'university.degree', 'unknown')
 default: has credit in default? (categorical: 'no','yes','unknown')
 housing: has a housing loan? (categorical: 'no','yes','unknown')
 loan: has a personal loan? (categorical: 'no','yes','unknown')
 contact: contact communication type (categorical: 'cellular','telephone')
 month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
 day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
 duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.
campaign: number of contacts performed during this campaign and for this client (numeric, includes the last contact)
pdays: number of days that passed by after the client was last contacted  from a previous campaign (numeric; 999 means the client was not previously contacted)
previous: number of contacts performed before this campaign and for this client (numeric)
poutcome: outcome of the previous marketing campaign (categorical: 'failure', 'nonexistent', 'success')
emp.var.rate: employment variation rate - (numeric)
 cons.price.idx: consumer price index - (numeric)
 cons.conf.idx: consumer confidence index - (numeric) 
 euribor3m: euribor 3 month rate - (numeric)
 nr.employed: number of employees - (numeric)

# Performance Evaluation

You are free to use any performance evaluation matrix. you use the following:
Importing necessary Libraries, and data preparation. 
Data validation, Statistical analysis, data overview, Data types.
Data manipulation/Data pre-processing, EDA.
Building model(choose appropriate algorithm), Model training, Model evaluation.
Requirements or Deliverables
Submit .ipynb ﬁle where all your code and outputs will be residing.
Each line must have comments.
Provide exploratory data analysis (EDA) for data insights and to support your modeling decisions.
Provide rationales for your data preparation decisions (e.g., missing imputation, one-hot encoding, etc.)
Run the model using a logistic regression algorithm.
Follow the instructions as given in the notebook.
