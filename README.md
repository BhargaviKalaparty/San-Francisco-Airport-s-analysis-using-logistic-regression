# San-Francisco-Airport-s-analysis-using-logistic-regression

Descriptive statistics such as mean, median and quartiles are calculated. Logistic regression is used on different attributes of dataset and best model is validated using the odd’s ratio, confidence intervals, AIC, R squared and p values.  Libraries: SciKit learn is used for statistical analysis of this dataset. 

# Dataset:

The dataset is adapted from a 2012 passenger survey from San Francisco airport (SFO). 
The variables of dataset are: 

good - the outcome variable, a binary measure of whether the passenger approved of the airport 1= good, 0 = not good 

dirty - a count of the number of locations (car park, restrooms, restaurants, etc) which the passenger felt were dirty 

wait - the number of hours the passenger spent at the airport between arrival and flying (not necessarily delays) 

lastyear - a count of the number of times the passenger flew out of SFO in the previous 12 months 

usa - binary, whether the passenger was flying to a destination in the USA (1) or another country (0)

# Research Scope and Visulaisations:

• A brief summary and explanation of descriptive statistics that are appropriate for each of the variables (mean and SD, or median and quartiles, or percentages). 
• A visualisation of ‘wait’ and ‘usa’ , highlighting the observations where the binary outcome was positive, with a brief explanation of what you can interpret from it.
• A logistic regression model using the predictor variables dirty, wait, last year and usa.
• Chosen ‘best’ model if different from the one above with a brief explanation on why its chosen.
• Provide the odds ratio and 95% confidence interval for all predictor models in your chosen ‘best’ model. Explain what these mean, you may want to discuss how a change in the value of the predictor variable impacts the predicted ‘risk’
• A classification table (confusion matrix), obtained based on classifying outcomes as “good" if the predicted risk is over 50%, and "bad" otherwise.

![image](https://github.com/BhargaviKalaparty/San-Francisco-Airport-s-analysis-using-logistic-regression/assets/149389777/6b70191c-f63d-435c-8f51-8cf9019bafde)
![image](https://github.com/BhargaviKalaparty/San-Francisco-Airport-s-analysis-using-logistic-regression/assets/149389777/9bbb58b2-bc90-4e2f-88b2-a15803dd474b)
![image](https://github.com/BhargaviKalaparty/San-Francisco-Airport-s-analysis-using-logistic-regression/assets/149389777/0563e457-82d8-4401-94aa-e55674aff2d1)
![image](https://github.com/BhargaviKalaparty/San-Francisco-Airport-s-analysis-using-logistic-regression/assets/149389777/b4086f04-bb04-4cab-a528-d8b5b91c95d2)
![image](https://github.com/BhargaviKalaparty/San-Francisco-Airport-s-analysis-using-logistic-regression/assets/149389777/21b44eb1-96c0-4edf-a437-50d9417138d9)
![image](https://github.com/BhargaviKalaparty/San-Francisco-Airport-s-analysis-using-logistic-regression/assets/149389777/f903484b-a2b4-4ff2-87d5-a7a66a709e9d)






