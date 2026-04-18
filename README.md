# Heart Disease Prediction Project

This project is a small healthcare data science workflow for predicting the presence of heart disease from patient health indicators.  
The analysis, preprocessing, model training, and evaluation are implemented in the Jupyter notebook [`heartDisease.ipynb`](heartDisease.ipynb).

## Project Description

The goal of this project is to build a machine learning model that can classify whether a patient is likely to have heart disease based on medical and demographic features. The notebook covers:

- Data loading and inspection
- Data cleaning and duplicate removal
- Exploratory data analysis and visualization
- Feature encoding and scaling
- Train/test split
- Logistic Regression model training
- Model evaluation
- Saving the trained artifacts with `pickle`
- Testing the model on new sample input

## Dataset

The dataset used in this project is stored in:

- [`dataset/HeartDiseaseTrain-Test.csv`](dataset/HeartDiseaseTrain-Test.csv)

### Dataset size

- Number of rows: `1025`
- Number of columns: `14`

### Target column

- `target`
- `0` means no heart disease
- `1` means heart disease detected

### Features

The dataset includes the following columns:

- `age`
- `sex`
- `chest_pain_type`
- `resting_blood_pressure`
- `cholestoral`
- `fasting_blood_sugar`
- `rest_ecg`
- `Max_heart_rate`
- `exercise_induced_angina`
- `oldpeak`
- `slope`
- `vessels_colored_by_flourosopy`
- `thalassemia`

## Model Artifacts

The trained model and preprocessing objects are saved in the `model` folder:

- [`model/heart_disease_model.pkl`](model/heart_disease_model.pkl)
- [`model/scaler.pkl`](model/scaler.pkl)
- [`model/label_encoders.pkl`](model/label_encoders.pkl)

## Model Performance

The notebook reports an accuracy of about `0.80` on the test set.

## Repository Structure

```text
HeartDiseasePrediction-Model-DataScience-Project/
├── dataset/
│   └── HeartDiseaseTrain-Test.csv
├── model/
│   ├── heart_disease_model.pkl
│   ├── label_encoders.pkl
│   └── scaler.pkl
├── heartDisease.ipynb
└── README.md
```

## How to Use

1. Open [`heartDisease.ipynb`](heartDisease.ipynb) in Jupyter Notebook or JupyterLab.
2. Run the notebook cells in order to reproduce the analysis and training workflow.
3. Use the saved `.pkl` files in the `model` folder if you want to load the trained model for inference.

## Batch Details

- Batch: `BCADS 23`
- Department/Program: `School of Computer Application`
- Academic Year: `2nd year, 4th semester`

## Team Member Details

- `Junaid Khan`
- `Uni. Rollno.: 1240258209`
- `Apoorv Sharma`
- `Uni. Rollno.: 1240258116`
- `Bipendra Kumar Pandey`
- `Uni. Rollno.: 1240258150`

