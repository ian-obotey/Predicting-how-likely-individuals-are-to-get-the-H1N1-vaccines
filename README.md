# Predicting-how-likely-individuals-are-to-get-the-H1N1-vaccines
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://www.washingtonpost.com/blogs/monkey-cage/files/2015/02/crop_358bigstock-vaccination-6365007.jpg)
# Overview
Vaccination is a key technique used to fight diseases. It is specifically helpful in fighting infectious diseases. Through the use of immunization the spread of diseases can be reduced because it provides herd immunity.
The aim of this project is to predict whether individuals got the H1N! flu vaccine based on data obtained from the United States National 2009 H1N1 flu survey.
The respondents were asked whether they received the H1N1 flu vaccine in conjuction with questions about themselves that provided data about various features such as whether they had health insurance or if they were health workers.
# Business Understanding 
A vaccine for the H1N1 flu virus became publicly available in October 2009. In late 2009 and early 2010, the United States conducted the National 2009 H1N1 Flu Survey. 
The aim of the survey was to find out if individuals took the vaccine or not. The classification model in this project will help know whether one took the vaccine or not based on certain traits. 
In the future this study can then be used by the stakeholders in the public health sector to know which groups of the population to target for vaccination.
# Data understanding
The data for this project was obtained from .It contains 35 features investigated from 26707 observations which were the responses provided to the survey questions.
# Modeling
Our Baseline model was a simple logistic regression model fitted on the training set without feature selection it had an f1 score of 43%.

The second model used was the K-Nearest Neighbors (KNN) model. It was built after feature selection was performed using the most important features. It had an f1 score of 36%.

The third model we used was the Decision Tree model.It was built without hyperparameter tuning, resulting in poor performance. With an f1 score of 37%.

The final model was a Decision Tree model with hyperparameter pruning.This  Improved model after hyperparameter tuning, leading to a higher F1 score of 78%.
# Evaluation
After experimenting with the different models we settled on the decision tree model that was
tuned by hyperparameters. This is because it met the success criteria by recording an f1 score of 78%. The first three models could not handle
the nature of data presented. This is why evn though the accuracyscore was high, the f1 score remained low. 
# Conclusion
* It would be advisable to conduct future interviews in person so as to obtain
honest opinions.

* The interviewers should attempt to find more data as to the particular reasons 
that one does not want to take the vaccines and address this issues.

* There should be more interviews being conducted to avoid the reliance on old 
datasets such as this one.

* The findings of this research acknowledged the importance of public awarness 
therefore the administrators should act on this.


