# Credit-Risk-Prediction-using-supervised-machine-learning
Build a machine learning model that attempts to predict whether a loan will be approved or not.

**Introduction**
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.
Use this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.

**Problem**
Create and compare two models on this data: a logistic regression, and a random forests classifier. Before creating, fit, and score the models, make a prediction as to which model you think will perform better. You do not need to be correct! Write down (in markdown cells in your Jupyter Notebook) your prediction, and provide justification for your educated guess.

**Analysis**
The dataset does not contain any null values and consists of integers or floats, so minimal data cleansing was required before testing.The data presents a positive trend which is shown with the use of a histogram.

**Logistic Regression Model**
After testing the two models head to head, it's clear that logistic regression presents a higher level of accuracy.Comparing traditional classification report with the use of GaussianNB Classification Report, interestingly presents slightly different data

**Random Forest Classifier**
When we compare both training and testing scores, it becomes clear that there is not a significant difference between the two models.
The bar chart provides a visual representation of the features. Interestingly, Feature 5 performed the worst while Feature 1 performed significantly better.

**Conclusion**
Both models show signs of positive trends. Although there wasn't a significant difference between both training models, it is clear Logistic Regression Model peformed better than the Random Forest Classifier
