# Supermarket Analysis

## Introduction
This repository contains a data analysis project focused on performing an Exploratory Data Analysis (EDA) on the UCI Machine Learning Repository dataset related to heart disease diagnosis. The project aims to understand the factors that may contribute to heart disease and create insightful visualizations using both Python and Tableau/PowerBI.

## Dataset Description
The dataset provided by the UCI Machine Learning Repository contains 76 attributes related to heart disease diagnosis. However, all published experiments and our project focus on a subset of 14 essential attributes. The "goal" field represents the presence of heart disease in patients and is integer-valued from 0 (no presence) to 4. For our analysis, we simplify the problem by distinguishing between presence (values 1, 2, 3, 4) and absence (value 0) of heart disease.

The dataset has been processed to ensure patient privacy, with names and social security numbers replaced by dummy values. The primary data file available is the Cleveland database, which is widely used in machine learning research for coronary artery disease diagnosis.

The 14 attributes used in this project are as follows:

   Age (age): Age of the patient in years.
   Sex (sex): Sex of the patient (1 = male; 0 = female).
   Chest Pain Type (cp): Type of chest pain experienced by the patient.
   Value 1: Typical angina
   Value 2: Atypical angina
   Value 3: Non-anginal pain
   Value 4: Asymptomatic
   Resting Blood Pressure (trestbps): Resting blood pressure in mm Hg on admission to the hospital.
   Serum Cholestoral (chol): Serum cholestoral level in mg/dl.
   Fasting Blood Sugar (fbs): Fasting blood sugar > 120 mg/dl (1 = true; 0 = false).
   Resting Electrocardiographic Results (restecg):
   Value 0: Normal
   Value 1: Having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
   Value 2: Showing probable or definite left ventricular hypertrophy by Estes' criteria.
   Maximum Heart Rate Achieved (thalach).
   Exercise Induced Angina (exang): Exercise-induced angina (1 = yes; 0 = no).
   ST Depression Induced by Exercise (oldpeak): ST depression induced by exercise relative to rest.
   The Slope of the Peak Exercise ST Segment (slope):
   Value 1: Upsloping
   Value 2: Flat
   Value 3: Downsloping
   Number of Major Vessels Colored by Flourosopy (ca): Number of major vessels (0-3) colored by flourosopy.
   Thalassemia (thal):
   Value 3: Normal
   Value 6: Fixed defect
   Value 7: Reversible defect
   Diagnosis of Heart Disease (num): The predicted attribute for angiographic disease status.
   Value 0: < 50% diameter narrowing
   Value 1: > 50% diameter narrowing (in any major vessel: attributes 59 through 68 are vessels)

## Project Structure
The project is organized into the following directories and files:

   /data: Contains the dataset files, including the processed Cleveland database and four unprocessed files.
   /python: Includes Jupyter Notebook files for performing EDA using Python.
   /tableau: Holds Tableau dashboard files.
   /powerbi: Holds PowerBI dashboard files.

## How to Reproduce the Analysis

1. Download the dataset from the UCI Machine Learning Repository and place it in the /data directory.
2. Explore the EDA using Python by running the Jupyter Notebook files in the /python directory.
3. Visualize the data using Tableau by opening the Tableau dashboard files in the /tableau directory.
4. Visualize the data using PowerBI by opening the PowerBI dashboard files in the /powerbi directory.

## References
R. Detrano, A. Jánosi, W. Steinbrunn, M. Pfisterer, J. Schmid, S. Sandhu, K. Guppy, S. Lee, V. Froelicher. (1989). "International application of a new probability algorithm for the diagnosis of coronary artery disease." Published in the American Journal of Cardiology.

## Dataset Citation
Please cite the original dataset if you use it in your research:

Cleveland Clinic Foundation (creator), First Hungarian Reformed Church of Pasadena (donor), Hungarian Institute of Cardiology, Budapest (donor), University of California, Irvine, School of Information and Computer Science (distributor). (1988). Heart Disease Data Set. UCI Machine Learning Repository. Irvine, CA: University of California, School of Information and Computer Science.
