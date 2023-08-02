# Diabetes-Prediction
## Task:
Predicting whether the person is diabetic or non-diabetic
## Dataset:
The main object of the dataset is to predict diagnostically whether a person has diabetes or not based on certain measurements. <br/>
The dataset contains different medical predictor variables and one target variable which is 'Outcome'. The features include Pregnancy, insulin, Glucose, Blood Pressure, Skin Thickness, BMI and Diabetes Pedigree Function. The dataset contains data from only female candidates.</br></br>
Source: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database
## Steps involved in the task:
<b>1. Import Libraries: </b><br/>
Libraries used are NumPy, pandas,sklearn, StandarScaler and SVM. </br><br/>
<b>2. Data Collection and Analysis: </b></br>
Import the dataset using pandas's read_csv function. Further, make use of functions such as shape, describe, value counts and group by to analyse the data.</br>
Subsequently, split the target ('Outcome') from the dataset.</br><br/>
<b>3. Data Standardization:</b></br>
The numerical variation between the data of different features is more in the given dataset, to resolve this issue we make use of the Standard Scaler library to scale the values.<br/><br/>
<b>4. Split the dataset: </b></br>
Next, we split the dataset as training and testing sets using <b>train_test_split</b> function. As 20% data is for testing and the rest for training.</br><br/>
<b>5. Building the model:</b></br>
We used <b>Support Vector Machine</b> to build the model. SVM is a supervised machine learning model that used classification algorithms for two-group classification problems. </br><br/>
<b>6. Model Evaluation: </b></br>
Accuracy Score for Trained data comes out to be: 78%<br/>
The accuracy Score for test data comes out to be: 77%<br/><br/>
<b>7. Building a predictive model: </b></br>
The final step is to build a system which will be able to predict using some random data as input to the created model.<br/><br/><br/><br/>

Reference: Project 2: Diabetes Prediction using Machine Learning with Python | End To End Python ML Project, 
Siddhardhan, https://www.youtube.com/watch?v=xUE7SjVx9bQ&list=PLfFghEzKVmjvuSA67LszN1dZ-Dd_pkus6&index=3
