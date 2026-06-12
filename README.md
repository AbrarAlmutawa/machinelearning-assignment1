
# Medical Students Dataset 

##  Dataset Overview

This project performs Exploratory Data Analysis (EDA) on a dataset containing medical and health-related information of students. The dataset includes demographic details, physical measurements, and health indicators.

The dataset consists of **199,999 records** and **13 features**, making it suitable for comprehensive analysis.

---

##  Features Description

| Column Name    | Description                        |
| -------------- | ---------------------------------- |
| Student ID     | Unique identifier for each student |
| Age            | Age of the student                 |
| Gender         | Gender (Male/Female)               |
| Height         | Height of the student (cm)         |
| Weight         | Weight of the student (kg)         |
| Blood Type     | Blood group (A, B, AB, O)          |
| BMI            | Body Mass Index                    |
| Temperature    | Body temperature                   |
| Heart Rate     | Heart rate (beats per minute)      |
| Blood Pressure | Blood pressure level               |
| Cholesterol    | Cholesterol level                  |
| Diabetes       | Diabetes status (Yes/No)           |
| Smoking        | Smoking status (Yes/No)            |

---

##  Data Cleaning

Several preprocessing steps were applied to ensure data quality:

* Checked for missing values across all columns
* Identified and removed duplicate records
* Converted data types where necessary
* Replaced missing values:

  * Numerical columns → filled using **median**
  * Categorical columns → filled using **mode**
* Treated `Student ID` as an identifier rather than a feature for analysis

###  Why Cleaning Was Needed

* Missing values can distort analysis results
* Duplicate rows can lead to incorrect conclusions
* Incorrect data types prevent proper calculations
* Clean data improves reliability of insights

---

##  Exploratory Data Analysis (EDA)

The following analyses and visualizations were performed:

###  Univariate Analysis

* Distribution of Age
* Distribution of BMI
* Distribution of Height and Weight
* Distribution of Cholesterol

###  Categorical Analysis

* Gender distribution
* Blood type distribution
* Diabetes status
* Smoking status

###  Bivariate Analysis

* Height vs Weight relationship
* BMI comparison by Gender
* Cholesterol levels by Diabetes status

###  Correlation Analysis

* Heatmap of numerical features to identify relationships

---

##  Key Insights

* Most students fall within a similar age range, indicating a consistent population group
* BMI values vary, with some potential outliers
* Height and weight show a positive relationship
* Certain blood types are more common than others
* The majority of students do not have diabetes
* Smoking prevalence varies among students
* Some health indicators such as cholesterol and blood pressure show variation across individuals

---

##  Conclusion

This EDA process helped in understanding the structure and quality of the dataset. After cleaning, the data became suitable for analysis and visualization. The insights obtained provide a better understanding of student health patterns and can be used for further machine learning tasks such as prediction or classification.

---

##  Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

##  Files Included

* `medical_students_dataset.csv` → Dataset file
* `EDA_notebook.ipynb` → Jupyter Notebook with full analysis
* `README.md` → Dataset description and project summary

---
