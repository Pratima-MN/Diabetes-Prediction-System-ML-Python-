# Diabetes-prediction-using-Machine-learning
A project on Machine Learning titled as "Diabetic prediction system" developed using Logistic Regression method

Diabetes is a type of chronic disease which is more common among the people of all age groups. Predicting this disease at an early stage can help a person to take the necessary precautions and change his/her lifestyle accordingly to either prevent the occurrence of this disease or control the disease (For people who already have the disease).

DATA SELECTION AND FEATURE EVALUATION:
The first steps involve selecting the dataset for the model and evaluating its features. For this paper, the first dataset chosen is the PIMA Indian dataset. There are a total of nine features/variables, among which eight are predictor variables and 1 is the target variable. The features are as follows:
■ Pregnancies: Number of times the patient was pregnant.
■ Glucose: Plasma glucose concentration over two hours in an oral glucose tolerance test.
■ Blood Pressure: Diastolic blood pressure (mm Hg).
■ Skin Thickness: Triceps skin fold thickness (mm).
■ Insulin: Two-Hour serum insulin (mu U/ml).
■ BMI: Body mass index (weight in kg/(height in m)^2).
■ Diabetes Pedigree Function/DPF: A function that scores the likelihood of diabetes based on family history.
■ Age: In years.
■ Outcome: Class variable (0 if non-diabetic, 1 if diabetic). This is the target variable.

LOADING DATA:
The data, which is in the CSV format, is loaded to a variable. There are 768 data points in Dataset.

DATA PRE-PROCESSING
The missing values, null values and values equal to zero for the predictor variables need to be identified in the dataset. The predictor variables/features cannot have a zero value except for certain features, like for example the ‘Pregnancies’ feature in Dataset . These values need to be replaced with the mean values of the column. This is an important step to increase the accuracy of prediction, as faulty values increase the chances of incorrect predictions.

TRAINING AND TESTING:
The data is split into training and testing sets. The common split ratios are 80:20 and 70:30. In this project, the data is split in the ratio of 80:20, i.e. 80% for training and 20% for testing.
A Logistic Regression algorithm is used to make the predictions and check for the accuracy. The execution time is also calculated.

#SCREEN SHOTS:

![image](https://user-images.githubusercontent.com/98044958/189970658-070f90af-eddf-4fab-8bfb-891fa3e5ba21.png)


![image](https://user-images.githubusercontent.com/98044958/189970740-99f74e44-7b72-46ee-b542-2f4c5bfb4033.png)


![image](https://user-images.githubusercontent.com/98044958/189970839-f2472878-3e41-4003-96d0-d0b4679e403e.png)


![image](https://user-images.githubusercontent.com/98044958/189970931-64742604-c34c-404d-a8d7-bdfdd69037c6.png)
