# Heart Disease Prediction Using Random Forest
Here we'll create a model for heart disease prediction Using Random Forest, so that they can take some action to be prepared.

**Dataset Source**-https://www.kaggle.com/datasets/dileep070/heart-disease-prediction-using-logistic-regression

**Tools used**- Jupyter notebook 

**Language and Packages uesd**- Python (Pandas,Numpy,Matplotlib,Sklearn)

## Data Cleaning
The data is imported and checked troughly for any irregularities and the dirty data is cleaned for smooth exploration .

## Data Exploration 
The data is explored to find relationships and insights present.

**Key Findings:**

1.Most number of patients are between the ages of 40-50 , followed by 50+ .

2.Close to 50% of patients(48.9%) are current smokers who smokes between 0-20 cigerattes per day.

3.Majority of Patients has cholestrol above 200.

4.Average BMI of the patient is 25.

5.More than 95% of the patients are not diabetic(97%) , not had stroke (99%) and not on BP medication (96%).

6.55% of the patients in the dataset are females.

## Random Forest Model
The data is preprocessed to form a test,train split which is then used to create the model.

The model is then evaluated which has an **average accuracy of 85%**.

The model is also used to predict the possibilty of heart disease in an imaginary patient A .
