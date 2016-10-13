A collection of classification projects built with Scikit learn or implemented from scratch in Python.

Some of the projects are built upon projects in the classification class I took on Coursera from UW.

#### [Classify Amazon review data with logistic regression](https://github.com/ExLupi/Classification_projects_in_Python/blob/master/1_Amazon_reviews/LogisticRegression_AmazonReview.ipynb)


Predict whether a review is positive or negative with bag-of-word features and logistic regression.

- extracted bag-of-word features with CountVectorizer in scikit learn
- compared two classification models: classify with the sign of score or a logit link
- compared the effect of vocabulary size on classifying Amazon review data
- benchmarked with majority-class classifier


#### [Training logistic regression models with gradient ascent and regularizations from scratch](https://github.com/ExLupi/Classification_projects_in_Python/blob/master/2_GradientDescent_for_LogReg/LogisticRegression_gradientdescent_regularization.ipynb) 

- implemented logistic regression with gradient descent algorithm from scratch
- performed sentiment analysis on curated Amazon review data
- explored effects of regularization with logistic regression


#### [Predicting loan defaults with decision trees](https://github.com/ExLupi/Classification_projects_in_Python/blob/master/3_Predicting_LoanDefault_DecisionTrees/Predicting_loan_defaults_with_decision_trees.ipynb)


In this project, I use past data from peer-to-peer lending company the LeandingClub to predict whether a future loan is likely to be paid off or default.

- exploritory data analysis on loan data
- data cleaning and feature extraction 
- building a decision tree classifier with sklearn
- validate the model to avoid over-fitting


#### [Building binary decision trees from scratch and analyzing effects of regularizations](https://github.com/ExLupi/Classification_projects_in_Python/blob/master/3_Predicting_LoanDefault_DecisionTrees/Building_BinaryDecisionTrees_from_scratch_and_pruning.ipynb)

- implemented decision tree models with numpy and pandas
- implemented various methods of regularization to prevent overfitting
- used the loan defaults data to analysis the effect of limiting (1) maximum tree depth (2) minimum node size (3) minimum error gain
