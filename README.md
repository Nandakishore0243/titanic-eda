# Titanic EDA Project 🚢

## 📌 Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand factors affecting passenger survival.

---

## 📂 Dataset
- Dataset: Titanic Dataset (CSV)
- Features include: Age, Sex, Fare, Pclass, SibSp, Parch, Survived

---

## ⚙️ Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Analysis Performed

### 1. Data Cleaning
- Handled missing values in Age
- Dropped Cabin column due to high missing data

### 2. Visualizations
- Age Distribution
- Fare Boxplot (Outliers detection)
- Survival by Gender
- Age vs Fare Scatter Plot
- Correlation Heatmap

---

## 🔍 Key Insights
- Female passengers had higher survival rate
- Higher class passengers (Pclass 1) survived more
- Fare is positively related to survival
- Age has minimal impact on survival
- Most passengers were between 20–40 years
- Fare contains many outliers

---

## 📁 Project Structure


titanic-eda/
│── data/
│ └── titanic.csv
│
│── images/
│ ├── age_distribution.png
│ ├── age_fare.png
│ ├── fare_boxplot.png
│ ├── heatmap.png
│ └── survival_gender.png
│
│── notebook/
│ └── eda.ipynb
│
│── report/
│ └── report.pdf
│
│── README.md


---

## 📌 Conclusion
Survival depended mainly on gender, passenger class, and fare rather than age.

---

## 🚀 Author
Nanda Kishore
