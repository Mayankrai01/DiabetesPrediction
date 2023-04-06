
## Diabetes Predictor
> Predict Diabetes using Machine Learning.

In this project, our objective is to predict whether the patient has diabetes or not based on various features like *Glucose level, Insulin, Age, BMI*. We will perform all the steps from *Data gathering to Model Creation.* During Model evaluation, we compare various machine learning algorithms on the basis of accuracy_score metric and find the best one. Then we create a web app using Flask which is a python micro framework.


# About Dataset
> Context
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to predict based on diagnostic measurements whether a patient has diabetes.

>Content
Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

# Attribute Information
1. Pregnancies: Number of times pregnant
2. Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
3. BloodPressure: Diastolic blood pressure (mm Hg)
4. SkinThickness: Triceps skin fold thickness (mm)
5. Insulin: 2-Hour serum insulin (mu U/ml)
6. BMI: Body mass index (weight in kg/(height in m)^2)
7. DiabetesPedigreeFunction: Diabetes pedigree function
8. Age: Age (years)
9. Outcome: Class variable (0 or 1)

# Steps

1. Data Collection
2. Data Pre-Processing
3. Exploratory Data Analysis
4. Feature Engineering
5. Feature Selection
6. Model Building

# Model Building 
Logistic Regression model was used for this particular dataset. Hyperparameter tuning was applied on various independent variables to get maximum efficiency for the model. We were able to predict whether a person was diabetic or not with precision upto 90% and 80% accuracy.


# Screenshots

![image](https://user-images.githubusercontent.com/103130321/230306138-8b1e639b-7456-413e-91a3-d662e656566a.png)
![image](https://user-images.githubusercontent.com/103130321/230305978-694c1a37-dcf4-4d9c-bd25-4c97879120a1.png)
![image](https://user-images.githubusercontent.com/103130321/230306055-d8368e0b-0111-457b-b0ee-9546a01f26fe.png)


# Installation

- Clone this repository and unzip it.

- After downloading, `cd` into the `root` directory.

- Begin a new virtual environment with Python 3 and activate it.

- Install the required packages using 
   `pip install -r requirements.txt`

- Execute the command:
   `python application.py`

- Open http://127.0.0.1:5000/ in your browser.
