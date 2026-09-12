# 🚢 Titanic Dataset Exploratory Data Analysis

## Syntecxhub Data Science Internship — Task 3

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to identify patterns associated with passenger survival.

## 📌 Project Objective

The objective of this project is to analyze the Titanic passenger dataset and understand how demographic and travel-related characteristics are associated with survival.

The analysis includes:

- Dataset structure and data type inspection
- Missing value analysis and data cleaning
- Overall passenger survival analysis
- Survival analysis by sex
- Survival analysis by passenger class
- Survival analysis by age groups
- Age distribution analysis using a violin plot
- Fare distribution analysis using a boxplot
- Combined analysis of sex and passenger class
- Summary of key insights

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## 📊 Dataset

The project uses the Titanic dataset available through the Seaborn library.

The dataset contains **891 passenger records** and includes attributes such as:

- Survival status
- Passenger class
- Sex
- Age
- Fare
- Embarkation location
- Family-related information

## 🧹 Data Cleaning

The dataset contained missing values in several columns.

- Missing `age` values were filled using the median age.
- Missing `embarked` and `embark_town` values were filled using their mode.
- The `deck` column was removed because approximately 77% of its values were missing.

After cleaning, the working dataset contained **891 rows with no remaining missing values**.

## 📈 Key Insights

1. The overall passenger survival rate was **38.38%**.
2. Female passengers had a survival rate of **74.20%**, compared with **18.89%** for male passengers.
3. First-class passengers had the highest survival rate (**62.96%**), while third-class passengers had the lowest (**24.24%**).
4. Children aged 0–12 had a survival rate of **57.97%**, while passengers above 60 had the lowest age-group survival rate at **22.73%**.
5. Female passengers maintained higher survival rates across all passenger classes. First-class females had a survival rate of **96.81%**, compared with **13.54%** for third-class males.

## 📁 Project File

`Syntecxhub_Task3_Titanic_EDA.ipynb`

The notebook contains the complete data cleaning, exploratory analysis, visualizations, insights, and conclusion.

## 🎯 Conclusion

The exploratory analysis identified substantial differences in survival across sex, passenger class, and age groups. Female passengers and first-class passengers showed higher survival rates, while senior passengers showed a comparatively lower survival rate.

These findings represent descriptive associations observed in the Titanic dataset and should not be interpreted as proof of causation.

## 👩‍💻 Internship

**Syntecxhub Data Science Internship — Task 3**

**Project:** Titanic Dataset Exploratory Data Analysis (EDA)
