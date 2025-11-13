# 📊 LA Crime Data Analysis (2020–2023)

This project performs an **Exploratory Data Analysis (EDA)** on the Los Angeles Crime Dataset from **2020 to 2023**.  
It includes data cleaning, preprocessing, visualization, and extraction of meaningful crime insights such as crime frequency, affected areas, victim demographics, and weapon usage.

---

## 📁 Dataset Information

The dataset used in this project is publicly available on Kaggle:

🔗 **Kaggle Dataset:**  
[Crime Data from 2020 to Present](https://www.kaggle.com/datasets/shubhamgupta012/crime-data-from-2020-to-present)

This dataset contains:
- Crime descriptions  
- LAPD reporting areas  
- Victim age, sex, and descent  
- Weapons used  
- Date & time of occurrence  
- Premise information  
- Location & cross-streets  

---

## 🧹 Data Cleaning & Preprocessing

The following preprocessing tasks were completed:

- Filled missing values for:
  - Victim Sex  
  - Victim Descent  
  - Premise Description  
  - Weapon Description  
  - MO Codes  
  - Crime Code fields (`Crm Cd 1–4`)  
  - `Premis Cd`, `Weapon Used Cd`  
  - Cross Street  
- Converted `DATE OCC` to proper datetime format  
- Extracted:
  - `Year`
  - `Hour`
  - `Time of Day` (Morning, Afternoon, Evening, Night)
  - `Age Group` (using bins)

---

## 📊 Analysis Performed

### 🔹 Top 5 Most Common Crimes
Identifies the most frequently occurring crime types.

### 🔹 Crime Count by LAPD Area
Counts crimes reported in each `AREA NAME`.

### 🔹 Crime Count by Year
Extracts the year and summarizes yearly crime totals.

### 🔹 Most Common Weapons Used
Lists the top 5 most frequently used weapons.

### 🔹 Crime Type + Area Combination Analysis
Shows common crime patterns for specific districts.

### 🔹 Victim Age Group Distribution
Victims grouped into:
- **0–18**
- **19–30**
- **31–50**
- **51–70**
- **71+**

### 🔹 Crimes by Time of Day
Creates time categories:
- **Night (0–6)**  
- **Morning (6–12)**  
- **Afternoon (12–18)**  
- **Evening (18–24)**  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn (optional for visualization)  
- Jupyter Notebook / Google Colab  
