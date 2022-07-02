## Heart Disease Classification

This notebook takes a look at the the data pertaining to heart attributes of various people and analyzes it to predict whether a person has a heart disease or not.

The approach this project takes : 

* Problem Definition
* Getting the data ready
* Exploratory Data Analysis
* Model Selection/Evaluation
* Features
* Experimentation

### Problem Definition

In a statement,
> "Given clinical data about a patient,can we predict whether or not they have a heart disease?"

### Getting Data Ready

For this project we will be using the UCI Heart disease dataset that can be found at heart-disease-dataset and https://archive.ics.uci.edu/ml/datasets/heart+disease

It is also available at https://www.kaggle.com/datasets/johnsmith88/


#### Data Dictionary

* age - age in years
* sex - (1 = male; 0 = female)
* cp - chest pain type
* trestbps - resting blood pressure (in mm Hg on admission to the hospital)
* chol - serum cholestrol in mg/dl
* fbs - (fasting blood sugar &gt 120 mg/dl) (1 = true; 0 = false)
* restecg - resting electrocardiographic results
* thalach - maximum heart rate achieved
* exang - exercise induced angina(1 = yes; 0 = no)
* oldpeak - ST depression induced by exercise relative to rest
* slope - the slope of the peak exercise ST segment
* ca - number of major vessels (0-3) colored by fluorosopy
* thal - 1 = normal; 2 = fixed defect; 3 = reversable defect
* target - presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.

> Since Data has no missing values and is already in the numerical form, we can move  on to Exploratory Data Analysis

### Exploratory Data Analysis

Making observations by analysing the data using various tools.

#### Libraries Used

* pandas
* matplotlib
* numpy

#### Observation 1:

Out of 303 records, It was found that 165 patients had a heart disease. That is a approximately **54.46%** of the total records.

 ![Heart Disease Value Counts](Target%20Value%20Counts.png)


 #### Observation 2:

 * 72 out of 96 women have a heart disease **i.e 75%** of women show signs of heart disease.

* 93 out of 207 men have a heart disease **i.e 44.93%** of men show sgins of heart disease

![target vs sex](https://user-images.githubusercontent.com/76565276/177000643-fe522790-b02c-4659-8a1b-b4547ef9a1ec.png)

