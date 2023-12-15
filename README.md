# Exploratory Data Analysis of Health care Data

## Overview

This repository contains Python code for conducting Exploratory Data Analysis (EDA) on a healthcare dataset. The analysis includes importing necessary libraries, checking for errors, transforming date columns, converting data types, performing summary statistics, exploring demographics in the dataset, analyzing the distribution of medical conditions by age, investigating the relationship between medical conditions and admission duration, examining medical conditions and test results by age, visualizing correlations and reporting insigths.
Dataset Information

    Source: [Kaggle(https://www.kaggle.com/datasets/prasad22/healthcare-dataset/data)]
    Size: 1.1mb
    Features: 
    - Age: The age of the patient at the time of admission, expressed in years.
    - Gender: Indicates the gender of the patient, either "Male" or "Female."
    - Blood Type: The patient's blood type, which can be one of the common blood types (e.g., "A+", "O-", etc.).
    - Medical Condition: This column specifies the primary medical condition or diagnosis associated with the patient, such as "Diabetes," "Hypertension," "Asthma," and more.
    - Date of Admission: The date on which the patient was admitted to the healthcare facility.
    - Doctor: The name of the doctor responsible for the patient's care during their admission.
    - Billing Amount: The amount of money billed for the patient's healthcare services during their admission. This is expressed as a floating-point number.
    - Admission Type: Specifies the type of admission, which can be "Emergency," "Elective," or "Urgent," reflecting the circumstances of the admission.
    - Discharge Date: The date on which the patient was discharged from the healthcare facility, based on the admission date and a random number of days within a realistic range.
    - Test Results: Describes the results of a medical test conducted during the patient's admission. Possible values include "Normal," "Abnormal," or "Inconclusive," indicating the outcome of the test.

    Format: csv

### Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn

#### Analysis Steps
##### Importing Libraries and Loading Data:
        Used Pandas, NumPy, Matplotlib, and Seaborn to facilitate data analysis.
        Loaded the healthcare dataset into a Pandas DataFrame.
###### Error Checking:
        Checked for missing values, outliers, and inconsistencies in the dataset.
###### Data Transformation:
        Converted two date object columns to timedelta64 types for time-based analysis.
###### Data Type Conversion:
        Converted timedelta64 and float columns to integer types for better compatibility and analysis.
###### Summary Statistics:
        Computed and visualized summary statistics for key features in the dataset.
##### Formulating Questions:
        Developed specific questions to guide further analysis and exploration of the dataset.
##### Demographic Exploration:
        Explored demographic information within the dataset.
##### Distribution of Medical Conditions by Age:
        Analyzed the distribution of medical conditions across different age groups.
##### Relationship Between Medical Conditions and Admission Duration:
        Investigated the correlation between medical conditions and the duration of admission.
##### Medical Conditions and Test Results by Age:
##### Explored how medical conditions and test results vary with age.
##### Visualizing Correlation:
        Utilized visualizations to highlight correlations between different features in the dataset.
        
### Questions Explored
- The demographic of the patients – age, gender, blood group distribution.
- Medical condition distribution by age?
- Was billing amount affected by age, admission type and medical condition?
- Relationship between medical condition and admission duration.
- Medical conditions and test results and age.
