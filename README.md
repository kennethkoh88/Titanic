# Titanic

Applying data analytics using R on Titanic datasets 

Predict the survival on the Titanic by using Machine Learning techniques

Source: https://www.kaggle.com/c/titanic/data?select=test.csv

The training set should be used to build your machine learning models. 
For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. 
Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.

Data Dictionary

Variables	

1) survival:	Survival	0 = No, 1 = Yes

2) pclass:	Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd

3) sex:	Sex	

4) Age:	Age in years	
 
5) sibsp:	# of siblings / spouses aboard the Titanic	
 
6) parch:	# of parents / children aboard the Titanic	

7) ticket:	Ticket number	

8) fare:	Passenger fare	

9) cabin:	Cabin number	

10) embarked:	Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton

Variable Notes

pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.
