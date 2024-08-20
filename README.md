# Module 13 Challenge
## classification-challenge


## Background




The purpose of this challenge was to take a provided dataset, create two classification models, and determine which supervised machine learning model was more accurate.


Specifically, we were tasked with creating (1) a logistic regression model and (2) a random forest model to fit data from an Internet Service Provider and to determine which model was better at detecting spam.


## Installation




The following libraries and dependencies are required to successfully run the project:
- import pandas as pd
- from sklearn.model_selection import train_test_split
- from sklearn.metrics import accuracy_score
- from sklearn.linear_model import LogisticRegression
- from sklearn.ensemble import RandomForestClassifier




## Repository Files and Starter Code
- [Module 13 Starter Code/Dataset](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv)
- spam_detector.ipynb: completed notebook with data analysis and solutions/answers




## Methodology
The project was completed in five steps:
1. Split the data into training and testing sets using the *train_test_split* function
2. Scale the features using StandardScaler
3. Create a logistic regression model, train the model, test the model, and calculate its accuracy score. 
4. Create a random forest model, train the model, test the model, and calculate its accuracy score.
5. Evaluate both models and compare accuracy scores to predictions.




## Evaluation


My initial prediction was:


> My initial instinct is that a logistic regression model would be sufficient for a binary output of "spam" or "not spam." A random forest classifier might get too complicated by going through unnecessary steps in the decision tree. Perhaps it would be more useful for multiple filters.


After reviewing the accuracy scores of both the logistic regression and random forest models, however, I am forced to admit that my initial prediction was incorrect and oversimplistic. While both models had pretty good accuracy scores, the Random Forest Classifier Model performed better, with a score of about 97% compared to the 93% of the logistic regression model. I believe the model required a broader lens and more complexity. In order to perform most accurately, the model needed to go beyond just "spam" or "not spam" and consider what should be classified as "spam." This is a more multistep process than I envisioned, and benefitted from the structure of the decision trees.






## Resources Consulted
For this challenge, I consulted the [Module 13 Starter Code](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv) and my in-class slides, notes, and activities.

