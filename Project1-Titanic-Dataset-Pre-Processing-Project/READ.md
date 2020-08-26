This project aim is examine the data with Python

The data has been split into two groups:
->training set (train.csv) 
->test set (test.csv)

-About the Data of Titanic Dataset-

Survived: Survivors on Titanic ship 1, survivors 0,
TARGET PassengerId,
Passengers id Pclass,
Economic status : 1st = Upper 2nd = Middle 3rd = Lower Name,
Passengers names ,
Sex: Male / Female Age,
Ages of Passengers SlipSp,
brother / sister (1 or 0) Parch,
parent / child (1 or 0) 
Ticket: Ticket numbers Fare, 
Ticket price 
Cabin: Cabin number 
Embarked: Port names (C, Q, S) C = Cherbourg, Q = Queenstown, S = Southampton
Survived = TARGET VALUE

-Variable Notes-
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
