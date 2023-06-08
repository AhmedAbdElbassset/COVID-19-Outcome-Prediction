# COVID-19-Outcome-Prediction
Design different classifiers to the predict the outcome (death/recovered) when a new person is admitted to the hospital
# Project Description
The data used in this project will help to identify whether a person is going to recover from coronavirus symptoms or not based on some pre-defined standard symptoms. These symptoms are based on guidelines given by the World Health Organization (WHO).

This dataset has daily level information on the number of affected cases, deaths and recovery from 2019 novel coronavirus. Please note that this is a time series data and so the number of cases on any given day is the cumulative number.

The data is available from 22 Jan, 2020. Data is in “data.csv”.

The dataset contains 14 major variables that will be having an impact on whether someone has recovered or not, the description of each variable are as follows,

Country: where the person resides
Location: which part in the Country
Age: Classification of the age group for each person, based on WHO Age Group Standard
Gender: Male or Female
Visited_Wuhan: whether the person has visited Wuhan, China or not
From_Wuhan: whether the person is from Wuhan, China or not
Symptoms: there are six families of symptoms that are coded in six fields.
Time_before_symptoms_appear:
Result: death (1) or recovered (0)
It is required to design different classifiers to the predict the outcome (death/recovered) when a new person is admitted to the hospital. The data is already cleaned and preprocessed.

we will have to divide the data into three partitions: training, validation, and testing. You need to design the following classifiers:

K-Nearest Neighbors
Logistic Regression
Naïve Bayes
Decision Trees
Support Vector Machines
For each classifier, find the optimal hyperparameters.

we also need to compare the performance of all classifiers using different metrics such as the precision, recall, F1-score, and ROC/AUC curves.
