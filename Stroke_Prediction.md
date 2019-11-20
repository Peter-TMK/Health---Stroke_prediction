# HealthCare: Stroke Prediction Problem


## Objective:
Predict whether a Patient will have stroke or not, according to the data given.

## Meaning of the column variables

id-Patient ID

gender-Gender of Patient

age-Age of Patient

hypertension-0 - no hypertension, 1 - suffering from hypertension

heart_disease-0 - no heart disease, 1 - suffering from heart disease

ever_married-Yes/No

work_type-Type of occupation

Residence_type-Area type of residence (Urban/ Rural)

avg_glucose_level-Average Glucose level (measured after meal)

bmi-Body mass index

smoking_status-patient’s smoking status

stroke-0 - no stroke, 1 - suffered stroke

Lets start by loading the Train data and final Test data on which I submitted the results

### During the analysis of this dataset, it was seen that there were very wide non-relational differences between people with stroke and those without it, based on the predictors. Less than 5000 people out of 43400 sample individuals has a stroke. This renders the dataset an imbalance dataset. In this case, the predictive model could be biased and inaccurate

## In order to make a more balanced dataset, we adjust the number of samples given for the stroke column

## This approach reduced the number of rows given for every column to 10583 rows (in a more appropriate manner)

## One thing to note is that this data is imbalance despite undergoing a re-sampling, we shouldn't invest too much in these patterns. A more balanced dataset would achieve a great result.