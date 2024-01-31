# Diabetes_Prediction_Using_the-Random_Forest_Algorithm_to_Project_Diabetes_Potential_in_Patient_Data

## Description
Exploration of diabetes through data analysis using the Random Forest algorithm. This research seeks to predict the risk of diabetes in patients by utilizing advanced approaches, leading to a positive impact on earlier diagnosis and more effective treatment.

## Analysis Objective
This project was carried out to carry out a statistical approach to look at the factors that cause diabetes and predict patients who have the potential to develop diabetes.

## Data Collection
The dataset was obtained directly from GitHub via the following source: [Telco-Customer-Churn Dataset](https://github.com/arubhasy/dataset/blob/main/Telco-Customer-Churn.csv)

## Bahasa 
**Programming Language**: Python

**Libraries used**: numpy, pandas, matplotlib, seaborn, scikit-learn, scipy shapiro

## Data Analysis Procces
### 1. Data Understanding
Understanding this data includes the data type for each column, the volume of each variable, and a comparison of patients who are healthy and those predicted to have diabetes.

### 2. Data Preparation
- **Data Cleaning**: the method used to deal with null values ​​is the median. The choice of this method is identified using scipy.
- **Data Transformation**: Transform data by deleting unused columns.

### 3. Splitting Data
The division between training data and testing data uses a ratio of 70: 30 because the data volume is below 1000.

### 4. Modelling and Evaluation
The evaluation shows that the TN (True Negative) is 95 and the TP (True Positive) is 44. Based on the Classification Report, the KNN algorithm is considered better with the following evaluation results:

Accuracy: 72%
Precision: 79%
Recall: 77%
F1-Score: 78%
### 5. Identifikasi Variable yang Berpengaruh Terhadap Diabetes
Feature Importance menggunakan Random Forest menunjukkan bahwa variabel yang paling berpengaruh adalah Glukosa.

Kesimpulan: Pasien yang memiliki gula darah tinggi berpotensi lebih besar untuk terkena penyakit diabetes
