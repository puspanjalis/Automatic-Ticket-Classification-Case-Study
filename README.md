# Automatic-Ticket-Classification-Case-Study

> This assignment aims to create a model that can automatically classify customer complaints based on the products and services that the ticket mentions.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- What is the background of your project?

For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers. 

These customer complaints are unstructured text data; so, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. This becomes tedious as the company grows and has a large customer base.

In this case study, you will be working as an NLP engineer for a financial company that wants to automate its customer support tickets system. As a financial company, the firm has many products and services such as credit cards, banking and mortgages/loans. 

- What is the business problem that your project is trying to solve?

A model needs to be built a model that is able to classify customer complaints based on the products/services. By doing so, we can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

With the help of non-negative matrix factorization (NMF), an approach under topic modelling, we will detect patterns and recurring words present in each ticket. This can be then used to understand the important features for each cluster of categories. By segregating the clusters, we will be able to identify the topics of the customer complaints. 

We will be doing topic modelling on the .json data provided by the company. Since this data is not labelled, you need to apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:

- Credit card / Prepaid card
- Bank account services
- Theft/Dispute reporting
- Mortgages/loans
- Others 

With the help of topic modelling, you will be able to map each ticket onto its respective department/category. You can then use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, you can classify any new customer complaint support ticket into its relevant department.

We need to perform the following eight major tasks to complete the assignment:

- Data loading
- Text preprocessing
- Exploratory data analysis (EDA)
- Feature extraction
- Topic modelling 
- Model building using supervised learning
- Model training and evaluation
- Model inference

- What is the dataset that is being used?

The data set given to you is in the .json format and contains 78,313 customer complaints with 22 features. You need to convert this to a dataframe in order to process the given complaints.

## Conclusions

## Conclusion :

- 5 topics were indetified namely:

- Account Services
- Others
- Mortgage/Loan
- Credit card or prepaid card
- Theft/Dispute Reporting

Tried 4 models on the data with accuracies as follows:

| Model | Accuracy | 
| ----------- | ----------- | 
| Logistic Regression | 0.95 | 
| Decision Tree | 0.77 | 
| Random Forest | 0.74 | 
| Naive Bayes | 0.36 |


    
Therefore, the variables predicted by Lasso in the above bar chart as significant variables for predicting the price of a house.

## Technologies Used

- jupyter_client  7.3.5
- matplotlib  3.5.3
- numpy  1.23.2
- pandas  1.4.4
- seaborn  0.11.2
- statsmodels 0.11.1
- scikit-learn 1.1.2  
- nltk 3.6.5


## Contact
Created by [puspanjalis](https://github.com/puspanjalis) - feel free to contact me!
