# Diabetese Prediction
*This is a university project on practicing data science basics*

## Table of content
- [Topic & the Problem Statement](#topic-and-the-problem-statement)
- [Our Approach](#our-approach)
- [Dataset and Features Introduction](#dataset-and-features-introduction)
- [The Project Structure](#the-project-structure)
- [Conclusion](#conclusion)
- [Authors](#authors)

## Topic and the Problem Statement
Diabetes is a very common disease across the globe. Hence, it's really important to predict if somebody is suffuring from it or not. In this project we will develop a data science model to foretell wether a desired person has diabetes or not. The sooner somebody gets aware that they have diabetes the better they can manage to overcome it. 

## Our Approach
We constructed a model so as to use it in order to predict based on diagnostic measurements if a patient is daiabetic or not. We used a dataset to train our model using two different classification algorithms: logistic regression and Naive Bayes. By entering new person with their properties listed [here](#the-features), the model will give an output of eather 1 or 0, with 1 being positive and 0 being nagative.

## Dataset and Features Introduction
### The Dataset
The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases, and we downloaded it from [Kaggle web site](https://www.kaggle.com).
All patients here are females at least 21 years old of Pima Indian heritage. It has 768 records and 9 features.

### The Features
- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance testBlood
- Pressure: Diastolic blood pressure (mm Hg)
- SkinThickness: Triceps skin fold thickness (mm)
- Insulin: 2-Hour serum insulin (mu U/ml)
- BMI: Body mass index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction: Diabetes pedigree function
- Age: Age (years)
- Outcome: Class variable (0 or 1)

## The Project Structure
**The project consists of four phases.**
1. Dataset examining
  In this phase we used pandas to learn about the dataset. We learned about things such as the number of records and features, the data types and formats of the features and so on.
2. Data prepration
  During this part of the project, we first tried to discover wether or not the dataset includes dirty data and then tried to handle if so. We found that some of the features are containing missing values; to address the issue, we replace all the missing values with each feature's mean value.
3. Training the model
  After data cleaning, it was time to train the model. So we trained two models, for the sake of confidence and accuracy. Python sklearn library was a good choice to train the model based on Logistic Regression and Naive Bayes classification algorithms.
4. Model utilizing
  Once we were done with Model construction, we would use the model. providing the model with a person's properties listed [here](#the-features), we would predict wether or not he/she is diabetic.

## Conclusion
The project objective is to predict based on diagnostic measurements if a patient is daiabetic or not. The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases, and we downloaded it from [Kaggle web site](https://www.kaggle.com). After cleaning the dataset, we constructed two models using Logistic regression and Naive Bayes algorithms.

## Authors
Hikmatullah Mohammadi & Abdul Raouf Alizada