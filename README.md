# Task 2 – Univariate Analysis on Titanic Dataset

## 📌 Project Overview
This task is part of my internship where I performed **Univariate Analysis** on the Titanic dataset.  
The goal of this task is to explore individual features (one variable at a time) using statistical methods and data visualizations to gain meaningful insights.

---

## 📂 Folder Structure
SCT_DS_2/
│── data/
│ ├── train.csv
│ ├── test.csv
│── titanic_eda.ipynb
│── README.md


---

## 🔑 Steps Performed
### 1. Data Collection
- Downloaded Titanic dataset (`train.csv`, `test.csv`).
- Placed them inside the `data/` folder.

### 2. Data Loading
- Loaded the dataset using **Pandas** (`pd.read_csv`).

### 3. Data Inspection
- Checked shape, columns, and info of the dataset.
- Identified missing values and data types.

### 4. Univariate Analysis
- Analyzed **categorical features** (`Sex`, `Pclass`, `Embarked`, `Survived`).
- Analyzed **numerical features** (`Age`, `Fare`, `SibSp`, `Parch`).

### 5. Data Visualization
- Used **Matplotlib** and **Seaborn** for plots.
- Plots included:
  - Count Plots (for categorical variables).
  - Histograms & KDE plots (for numerical variables).
  - Pie charts (for proportions).
- Added **colorful & clear themes** for better readability.

### 6. Key Insights
- Majority of passengers were in **3rd class**.
- More **male passengers** than female.
- Females had a **higher survival rate** compared to males.
- Most passengers were **20–40 years old**.
- Fare distribution was **right-skewed** (few very high fares).

---

## 📊 Sample Visualizations
- **Survival Distribution**
- **Age Histogram**
- **Passenger Class Countplot**
- **Fare Distribution**

---

## ✅ Completed Checklist
- [x] Created repository `SCT_DS_2`
- [x] Added dataset (`train.csv`, `test.csv`)
- [x] Performed univariate analysis
- [x] Created visualizations (colorful & clear)
- [x] Documented insights
- [x] Added README file


---
👩‍💻 *Internship Project – Task 2 Completed Successfully*
