# Problem Statement
The datasets consist of several medical predictor (independent) variables and one target (dependent) variable, Outcome. Independent variables include the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.
and we need to predict whether have diabetes or not.

# Content
we actually have a few sample size (768 rows), so we will go with machine learning techniques to solve our problem.

This Dataset contains total (9) features

1-Pregnancies >>(Number of times pregnant)

2-Glucose >>(Plasma glucose concentration a 2 hours in an oral glucose tolerance test)

3-BloodPressure >> Diastolic blood pressure (mm Hg)

4-SkinThickness >> Triceps skin fold thickness (mm)

5-Insulin >> 2-Hour serum insulin (mu U/ml)

6-BMI >> Body mass index (weight in kg/(height in m)^2)

7-DiabetesPedigreeFunction >> Diabetes pedigree function

8-Age >> Age (years)

and the predicate column (Outcome) >> Class variable (0 or 1) 268 of 768 are 1, the others are 0


# Note
Outliers values   were found in the Independent variables   in order to remove them I split the data first in order to get rid of the outliers.

# conclusion

Modeles I used are (SVV && KNN).

1)SVM I got 

Accuracy is  80.51948051948052 %

2)KNN I got

Accuracy is  71.484375 %

