# Cardiovascular Risk Prediction



## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Cardiovascular diseases, including heart attacks and strokes, are among the leading causes of mortality and morbidity worldwide. Early identification of individuals at higher risk of developing cardiovascular diseases is critical for implementing preventive measures and timely medical interventions. The "Cardiovascular Risk Prediction" project leverages machine learning techniques to predict the likelihood of cardiovascular diseases based on a set of risk factors. By building accurate predictive models, this project aims to assist healthcare professionals in making informed decisions and improving patient outcomes.

## Dataset
The dataset used in this project is sourced from [here](https://drive.google.com/file/d/1cLHnV4i76jY4t5-dvZuXwntO5G3gYnJ0/view?usp=sharing). 


It contains a diverse collection of anonymized patient records, encompassing a range of relevant features, including:
Demographic:


Sex: male or female("M" or "F")

Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)

Education:- Education level (discrete)[1,2,3,4]

Behavioral:

is_smoking: whether or not the patient is a current smoker ("YES" or "NO")

Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)

Medical(history):

BP Meds: whether or not the patient was on blood pressure medication (Nominal)

Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)

Prevalent Hyp: whether or not the patient was hypertensive (Nominal)

Diabetes: whether or not the patient had diabetes (Nominal)

Medical(current):

Tot Chol: total cholesterol level (Continuous)

Sys BP: systolic blood pressure (Continuous)

Dia BP: diastolic blood pressure (Continuous)

BMI: Body Mass Index (Continuous)

Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though infact discrete, yet are considered continuous because of large number of possible values.)

Glucose: glucose level (Continuous)

Predictive variable(desired target):

10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”) (DV)


The data has been preprocessed and divided into training and testing sets, facilitating model development and evaluation.

## Installation
To run this project on your local machine, follow these steps:

1. Copy the file in google drive.


2. Run the Colab File.



## Usage
Once the project and its dependencies are installed, you can explore the dataset, train machine learning models, and make predictions using either the provided Jupyter Notebook or Python scripts.

The main files in this repository are:

- `cardiovascular_risk_prediction.ipynb`: Colab Notebook containing a detailed step-by-step process of data preprocessing, model 

## Models
Several classification models have been implemented for cardiovascular risk prediction:

- **Logistic Regression**: A simple and interpretable model used as a baseline for comparison.
  
- **Random Forest**: An ensemble model capable of handling non-linear relationships and capturing complex patterns in the data.
  
- **Support Vector Machine (SVM)**: A powerful algorithm for both linear and non-linear classification tasks.
  
- **Gradient Boosting**: A boosting algorithm that sequentially improves the performance of weak learners.

The model training code can be found in the Jupyter Notebook or Python scripts provided in this repository.

## Evaluation

To assess the performance of each model, we utilize a range of classification metrics, including:

- **Accuracy**: The proportion of correctly classified instances over the total number of instances.
  
- **Precision**: The ability of the model to correctly identify positive cases among the predicted positive cases.
  
- **Recall**: The ability of the model to correctly identify positive cases among the actual positive cases.
  
- **F1-score**: The harmonic mean of precision and recall, providing a balanced evaluation metric.
  
- **ROC-AUC**: The area under the Receiver Operating Characteristic curve, indicating the model's discriminatory power.

The evaluation results for each model are presented in the Jupyter Notebook.

## Contributing
Contributions to this project are highly appreciated! If you encounter any issues or have ideas to enhance the models or codebase, please don't hesitate to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute the code under the terms of this license.

---

We hope this comprehensive README provides you with all the necessary information to get started with your "Cardiovascular Risk Prediction" classification project. Should you require any further assistance or have questions, please feel free to reach out to us.

Let's contribute to better healthcare outcomes through accurate risk prediction! :heartbeat:
