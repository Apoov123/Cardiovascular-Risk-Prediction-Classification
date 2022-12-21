# Cardiovascular-Risk-Prediction-Classification
![Heart failure - shutterstock_1663310782](https://user-images.githubusercontent.com/102784806/208307488-57127cbc-4fe3-4b46-8707-a65f6648bbb5.jpg)


## Problem Statement

The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes. Variables Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors.

## Dataset summary

The dataset contains different columns of variables important for predicting the cardiovascular risk.

Demographic:

• Sex: male or female ("M" or "F")

• Sex: male or female ("M" or "F")

• Age: Age of the patient;(Continuous - Although the recorded age
    have been truncated to whole numbers, the concept of age is( continuous)

Behavioral:

• is smoking: whether or not the patient is a current smoker ("YES" or "NO")

• Cigs Per Day: the number of cigarettes that the person smoked on average in one day. (Can be considered continuous as one can have any number of cigarettes, even       half a cigarette.)
   
Medical(history)

 • BP Meds: whether or not the patient was on blood pressure medication (Nominal)

 • Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)

 • Prevalent Hyp: whether or not the patient was hypertensive (Nominal)

 • Diabetes: whether or not the patient had diabetes (Nominal)

Medical(current)

 • Tot Chol: total cholesterol level (Continuous)

 • Sys BP: systolic blood pressure (Continuous)

 • Dia BP: diastolic blood pressure (Continuous)

 • BMI: Body Mass Index (Continuous)

 • Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large          number of possible values.)

 • Glucose: glucose level (Continuous)

Predict variable (desired target)

 • 10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”) – DV  

## Conclusions

* We tried plotting all numerical variables with the dependent variables. From here we can conclude that,

* The major people who are having Cardiovascular Risk(CVR) are at the age of 50-70.

* The cholesterol level of people is the same for both kinds of people who are at risk of CVR and not at risk of CVR. Instead fewer people who are not at risk of CVR     are having high Cholesterol levels.

* If we take sysBP and diaBP together into consideration, then most of the people are having normal BP. So it's hard to conclude here about the CVR.

* Even though many people have a normal range of BMI, the people who are having high BMI, they are at risk of CVR.

* Many people are having normal heart rate ranges, so it's not appropriate to come into conclusion about the CVR at this stage.

* In glucose level, we can see some outliers in both kinds of people(who are at risk and not at risk). But the people who have high glucose levels are coming into the   category of CVR. So we can conclude that it's even one of the factors which may contribute to CVR.

The accuracy of some models were increased after hyper parameter tuning, still Adaboost and naive bayes are the best performing models.
Between those, if we compare Naive Bayes and Adaboost with accuracy and recall, Naive Bayes is the best performance model.


