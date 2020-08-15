# Titanic: Machine Learning from Disaster
Code for the Titanic Challenge on Kaggle, where the goal is to predict which passengers survived the Titanic shipwreck.


### The Challenge
From the competition homepage:

> In this competition, you’ll gain access to two similar datasets that include passenger information like name, age, gender, socio-economic class, etc. One dataset is titled `train.csv` and the other is titled `test.csv`.
>
> `train.csv` will contain the details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, also known as the “ground truth”.
>
> The `test.csv` dataset contains similar information but does not disclose the “ground truth” for each passenger. It’s your job to predict these outcomes.
>
> Using the patterns you find in the train.csv data, predict whether the other 418 passengers on board (found in `test.csv`) survived.


### Current Process:

- Picking out a subset of relevant attributes to train on
- Run RandomizedSearchCV and GridSearchCV to get the best hyper-parameters for a Random Forest Classifier
- Train best model on all data, make predictions and submit!
Make predictions


### TODO :
 - Fill in null values in Age (mean or median maybe)
 - Fill in null values in fare
 - Make Embarked a categorical variable (see if it helps)
 - Maybe use name somehow



### Authors
Raghav Raj Mittal, Nihal Shah
