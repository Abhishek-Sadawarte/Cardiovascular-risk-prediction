## Cardiovascular Risk Prediction using Machine learning 
Nowadays many health insuarance companies use patients past medical history to predict its future health and to decide premium, 
but this same can be use in Medical Institutes to predict is patient is on verge of risk of or not by analysing its past history. 
This is where machine learning algorithms come into play.  Machine Learning helps in predicting the Heart diseases, and the predictions made are quite accurate.

This is a classification problem, and there are many machine learning models for classification present. 
From those too many models I used following models with the help of scikit library. 

1.	Logistic Regression
2.	Decision Tree Classifier
3.	Random Forest Classifier
4.	Naïve bayes Classifier
5.	K Nearest Neighbor
6.	Support Vector Machine (SVM)
7.	Gradient Boosting
8.	Ada Boosting
9.	XG Boosting

## Objective 
The main Objective of our project is to predict whether given patien is on risk of 10 year coronory heart disease. 

## Data Description 
The dataset contains different columns of variables important for predicting the cardiovascular risk.
Demographic:

• Sex: male or female ("M" or "F")
• Age: Age of the patient;(Continuous - Although the recorded ages
have been truncated to whole numbers, the concept of age is( continuous)

Behavioral:

• is smoking: whether or not the patient is a current smoker ("YES" or "NO")
• Cigs Per Day: the number of cigarettes that the person smoked on average in one day. (Can be considered continuous as one can have any number of cigarettes, even half a cigarette.)

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
• Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)
• Glucose: glucose level (Continuous)

Predict variable (desired target)

• 10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”) – DV

## Libraries and Tools 
1. Numpy 
2. Pandas 
3. Scipy 
4. sklearn 
5. Seaborn 
5. Matplotlib 

## Conclusion 
1. Between those, if we compare Naive Bayes and Adaboost with accuracy and recall, Naive Bayes is the best performance model.
2. The Naive Bayes accuracy: 0.853
