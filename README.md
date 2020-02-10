# Inclusivity

This project build a model that predicts customers who are likely to stop paying premiums.

### Problem statement: 

75% of Inclusivity's customers will not have cover when they need it most (i.e. when a shock event occurs) because they have stopped paying premiums, which increases their vulnerability. The high churn also undermines Inclusivity's sustainability.

 

### Solution: 

I am building a model that predicts the propensity of customers to churn and the reasons for those who are likely churn through the use of interpretable machine learning methods. This will enable Inclusivity to tailor business interventions that keep our customers' cover active when it is at risk of being cancelled because of non-payment. Thus, more customers will be able to claim when needed.

 

### How data has been used: 

A very rich and varied data set has been compiled from Inclusivity's insurance data and Equity's banking data (Inclusivity's distribution partner). This data has been used to understand customer profiles and build the churn prediction model with application of interpretable machine learning methods.

 

#### Customer segment to benefit the most: 

Inclusivity's insurance product is being sold to Equity Bank's m-banking customers, who are predominantly from the mass market in Kenya. Customers who are the most vulnerable to income and expense uncertainty will benefit the most because Inclusivity will be in a position to identify those customers with active cover most at risk of being unable to make a premium payment. Inclusivity will further be able to provide tailored interventions based on the reasons for being at risk of churning. For example, based on reducing value of banking transactions. Cover for that customer could be temporarily reduced or suspended until their financial situation improves.


# How the Machine Learning models was deploy in Production as APIs (using Flask)

I remember the initial days of my Machine Learning (ML) projects. I had put in a lot of efforts to build a good model. I took expert advice on how to improve my model, I thought about feature engineering, I talked to domain experts to make sure their insights are captured. But then I came across a problem!

How do I implement this model in real life? I had no idea about this. All the literature I had studied till now focussed on improving the models. But I didn’t know what was the next step.

Therefore, I have created this guide – so that you don’t have to struggle with the question as I did. By end of this article, I will show you how to implement a machine learning model using Flask framework in Python.

### Contents

1.	Options to implement Machine Learning models
2.	What are APIs?
3.	Python Environment Setup & Flask Basics
4.	Creating a Machine Learning Model
5.	Saving the Machine Learning Model: Serialization & Deserialization
6.	Creating an API using Flask

#### Options to implement Machine Learning models

API-first approach: Web APIs have made it easy for cross-language applications to work well. If a frontend developer needs to use your ML Model to create a ML powered web application, they would just need to get the URL Endpoint from where the API is being served. 

### What are APIs?

An API is a (hypothetical) contract between 2 software’s saying if the user software provides input in a pre-defined format, the later with extend its functionality and provide the outcome to the user software. We’ll understand how to create our own Machine Learning API using Flask, a web framework in Python.

