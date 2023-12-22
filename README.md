# Loan-Eligibility-Prediction

<h2>Overview</h2>
This repository contains Python code for building a machine learning model to predict whether a person will get their loan approved or not. The model utilizes background information of the applicant such as gender, marital status, income, etc. The dataset used for training and testing the model is provided in the loan_data.csv file. The goal is to develop a machine learning model that predicts loan eligibility based on applicant information. This involves importing necessary libraries, loading the dataset, exploring the data, and preprocessing it for training.

<h2>Table of Contents</h2>

<h3>Data Exploration</h3>
In the Data Exploration part, we take a close look at our dataset. First, we check how many rows and columns we have. Then, we gather information about the types of data and if there are any missing values. Finally, we get some basic statistics to understand things like average and minimum values.

<h3>Exploratory Data Analysis</h3>
In Exploratory Data Analysis (EDA), we use visual tools to dig deeper into the data. We start with a pie chart to show the percentage of approved and not approved loans. Next, we use bar charts to see how loan approval relates to gender and marital status. We also use plots to understand the distribution of income and loan amounts and identify any extreme values.

<h3>Data Preprocessing</h3>
Before teaching our computer how to make predictions, we need to prepare our data. In this step, we turn words into numbers (label encoding), make sure we have enough examples of each type of loan approval (oversampling), and ensure our numbers are on a similar scale for fair comparison (standard scaling).

<h3>Model Development</h3>
Now, it's time to build our loan prediction machine! We choose a tool called Support Vector Classifier (SVC) and let it learn from our prepped data. We check how well it learned by looking at ROC AUC scores, which tell us how good it is at distinguishing between approved and not approved loans.

<h3>Model Evaluation</h3>
In the Model Evaluation stage, we carefully inspect how our model is performing. We use terms like ROC AUC scores and confusion matrix to see if our model is making the right predictions. It's like checking if our model is a good student by looking at its grades and where it got things right or wrong.

<h2>Conclusion</h2>
The model's performance might improve with a larger dataset. Further exploration and experimentation with different models could lead to better accuracy.

