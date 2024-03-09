# Predicting-how-likely-individuals-are-to-get-the-H1N1-vaccines
# Overview
Vaccination is a key technique used to fight diseases. It is specifically helpful in fighting infectious diseases. Through the use of immunization the spread of diseases can be reduced because it provides herd immunity.
The aim of this project is to predict whether individuals got the H1N! flu vaccine based on data obtained from the United States National 2009 H1N1 flu survey.
The respondents were asked whether they received the H1N1 flu vaccine in conjuction with questions about themselves that provided data about various features such as whether they had health insurance or if they were health workers.
# Business Understanding 
A vaccine for the H1N1 flu virus became publicly available in October 2009. In late 2009 and early 2010, the United States conducted the National 2009 H1N1 Flu Survey. The aim of the survey was to find out if individuals took the vaccine or not. The classification model in this project will help know whether one took the vaccine or not based on certain traits. In the future this study can then be used by the stakeholders in the public health sector to know which groups of the population to target for vaccination.
# Data understanding
The data for this project was obtained from .It contains 35 features investigated from 26707 observations which were the responses provided to the survey questions.
# Modeling
Two models were built for this project. The first base model was a logistic regression model. This model was fitted on the training set before any feature selection was done. The model was then fitted in the test data which resulted in an f1 score of. This model was considered to be a poorly perfroming model.
To improve on this a decision tree model was then used. Intitially it provided an f1 score of . On the use of hyperparameter tunning  the model improved and had an f1 score of .
# Evaluation
The final model had an f1 score of . B
# Conclusion
The public health sector should increase awareness about vaccines. Based on the finding that the higher the level of knowledge the higher the chances one would be vaccinated.
It is better to do this surveys in person based on the idea that people are more likely to be truthful in person.

