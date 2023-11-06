# San-Francisco-Airport-s-analysis-using-logistic-regression

Descriptive statistics such as mean, median and quartiles are calculated. Logistic regression is used on different attributes of dataset and best model is validated using the odd’s ratio, confidence intervals, AIC, R squared and p values.  Libraries: SciKit learn is used for statistical analysis of this dataset. 

# Dataset:

The dataset is adapted from a 2012 passenger survey from San Francisco airport (SFO). 
The variables of dataset are: 

Good - the outcome variable, a binary measure of whether the passenger approved of the airport 1= good, 0 = not good 

Dirty - a count of the number of locations (car park, restrooms, restaurants, etc) which the passenger felt were dirty 

Wait - the number of hours the passenger spent at the airport between arrival and flying (not necessarily delays) 

Lastyear - a count of the number of times the passenger flew out of SFO in the previous 12 months 

USA - binary, whether the passenger was flying to a destination in the USA (1) or another country (0)

# Reasearch Scope:

• A brief summary and explanation of descriptive statistics that are appropriate for each of the variables (mean and SD, or median and quartiles, or percentages). 
• A visualisation of ‘wait’ and ‘usa’ , highlighting the observations where the binary outcome was positive, with a brief explanation of what you can interpret from it.
• A logistic regression model using the predictor variables dirty, wait, last year and usa.
• Chosen ‘best’ model if different from the one above with a brief explanation on why its chosen.
• Provide the odds ratio and 95% confidence interval for all predictor models in your chosen ‘best’ model. Explain what these mean, you may want to discuss how a change in the value of the predictor variable impacts the predicted ‘risk’
• A classification table (confusion matrix), obtained based on classifying outcomes as “good" if the predicted risk is over 50%, and "bad" otherwise.
