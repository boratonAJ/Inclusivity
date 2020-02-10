# Inclusivity

This project build a model that predicts customers who are likely to stop paying premiums.


### How to deploy Machine Learning models in Production as APIs (using Flask)


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

an API is a (hypothetical) contract between 2 software’s saying if the user software provides input in a pre-defined format, the later with extend its functionality and provide the outcome to the user software. We’ll understand how to create our own Machine Learning API using Flask, a web framework in Python.

