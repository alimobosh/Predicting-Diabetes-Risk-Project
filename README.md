# Healthcare - Predicting Diabetes Risk Project

This project aims to predict diabetes risk using a dataset containing health-related features. The analysis is performed in a Jupyter Notebook (`Predicting Diabetes Risk Project11.ipynb`) using Python libraries for data manipulation, visualization, and machine learning.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Steps](#steps)
  - [Step 1: Import Libraries](#step-1-import-libraries)
  - [Step 2: Read Data](#step-2-read-data)
  - [Step 3: Data Preprocessing](#step-3-data-preprocessing)
- [Visualizations](#visualizations)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
The goal of this project is to build a predictive model to identify individuals at risk of diabetes based on features such as age, gender, BMI, blood pressure, glucose levels, physical activity, and family history. The project uses machine learning techniques, including Logistic Regression and Decision Tree classifiers, to predict diabetes outcomes.

## Dataset
The dataset used is `healthcare_diabetes.csv`, which contains the following columns:
- `PatientID`: Unique identifier for each patient (object)
- `Age`: Patient's age (integer)
- `Gender`: Patient's gender (Male/Female)
- `BMI`: Body Mass Index (float)
- `BloodPressure`: Blood pressure measurement (integer)
- `GlucoseLevel`: Glucose level (float)
- `PhysicalActivity`: Level of physical activity (Low/Medium/High)
- `FamilyHistory`: Family history of diabetes (Yes/No)
- `Diabetes`: Target variable indicating diabetes presence (0 = No, 1 = Yes)

The dataset contains 510 rows, with 35 missing values in `BMI` and `GlucoseLevel` columns. There are also 10 duplicate `PatientID` entries.

## Dependencies
The following Python libraries are required to run the notebook:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Install them using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
