Please read the "Machine Learning Engineer Nanodegree Capstone Report" PDF for further details.

Capstone proposal feedback link: https://review.udacity.com/#!/reviews/2268590


Project Overview
This project is the Capstone project of the Udacity Machine Learning Engineer Nanodegree. The data set contain simulated data that mimics customer behaviour on the Starbucks rewards mobile app. The data has been simplified so as to only contain one product. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks. Not all users receive the same offer, and that is the challenge to solve with this data set.
Problem Statement
The aim of this project is to create a model looking at customers who had either completed and offer without viewing or before they had viewed the offer and customers who did not complete the offer.
Once a model to predict whether a user would naturally have completed an offer has been created the evaluation can be extended and used to predict whether or not the users who had viewed and completed the offer would have done so naturally anyway and calculate whether the offers generated additional revenue.

References
•	Udacity Starbucks Challenge: https://d.docs.live.net/3cf38744fb5290a1/Documents/o%09https:/classroom.udacity.com/nanodegrees/nd009t/parts/2f120d8a-e90a-4bc0-9f4e-43c71c504879/modules/2c37ba18-d9dc-4a94-abb9-066216ccace1/lessons/4f0118c0-20fc-482a-81d6-b27507355985/concepts/480e9dc2-4726-4582-81d7-3b8e6a863450
•	sklearn
o	GradientBoostedClassifer: https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html
o	RandomForest Classifier: https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html#sklearn.ensemble.RandomForestClassifier
o	LogisticRegression: https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html
o	GridSearchCV: https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html
•	pandas
o	cut: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.cut.html
o	get_dummies: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.get_dummies.html
•	How to reverse an argsort: https://stackoverflow.com/questions/16486252/is-it-possible-to-use-argsort-in-descending-order
•	Confusion matrices and how to plot them: https://scikit-learn.org/stable/auto_examples/model_selection/plot_confusion_matrix.html
