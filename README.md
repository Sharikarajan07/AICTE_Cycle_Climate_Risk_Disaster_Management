# 🌍 AICTE Cycle 3 (2025) - Climate Risk & Disaster Management

## 📌 Project: AI-Powered Climate Risk Prediction & Disaster Management

### 📖 Overview

This project focuses on AI-powered climate risk prediction and disaster management. Using the EM-DAT dataset (1900–2021), we analyze global disaster patterns, prepare data for predictive modeling, and develop insights that can help in early warning systems and disaster preparedness.

## 📂 Dataset  
- **Source:** EM-DAT (Emergency Events Database), dataset file pre-downloaded and provided as `1900_2021_DISASTERS - emdat data.csv`
- **File Used:** `1900_2021_DISASTERS - emdat data.csv`  
- **Period:** 1900 – 2021  
- **Data Types:**  
  - Disaster type & subtype  
  - Country & region  
  - Date & year  
  - Human impact (deaths, injured, affected, displaced)  
  - Economic damages  

---

## ✅ Week 1 – Data Preprocessing & Initial Exploration  
**Objective:** Select a project theme (Climate Risk & Disaster Management), choose a dataset, and perform basic data understanding.  

### 🔎 Steps Completed  
1. Selected **Climate Risk & Disaster Management** as the project theme.  
2. Chose dataset: `1900_2021_DISASTERS - emdat data.csv` (from EM-DAT, pre-downloaded).  
3. Imported libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`.  
4. Loaded dataset into a DataFrame.  
5. Explored dataset using:  
   - `.info()` → dataset structure  
   - `.describe()` → summary statistics  
   - `.isnull().sum()` → missing values check  

📊 **Outcome:** Gained initial understanding of dataset structure, size, and quality. Ready for cleaning and deeper analysis in Week 2.  

---

## ✅ Week 2 – Exploratory Data Analysis (EDA), Transformation & Feature Selection  
**Objective:** Gain deeper insights, prepare dataset for ML modeling.  

### 🔎 Steps Completed  
1. **Exploratory Data Analysis (EDA):**  
   - Distribution of disaster types  
   - Trends across decades  
   - Top affected countries  
   - Correlation analysis  

2. **Data Transformation:**  
   - Normalized column names (lowercase + underscores)  
   - Encoded categorical variables (Label Encoding)  
   - Standardized numerical features  

3. **Feature Selection:**  
   - Applied statistical tests (ANOVA F-test, Mutual Information)  
   - Selected most relevant features for predictive modeling  

4. Saved processed dataset → `week2_features.csv`  

📊 **Outcome:** Dataset prepared for machine learning tasks (Week 3).  

---

## 🛠️ Technologies Used  
- **Python 3.x**  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Visualization:** Heatmaps, Count plots, Trend analysis  
- **Tools:** Jupyter Notebook / Google Colab, GitHub  

---

## 🚀 How to Run  

```bash
# Clone repository
git clone https://github.com/YourUsername/AICTE_Cycle_Climate_Risk_Disaster_Management.git
cd AICTE_Cycle_Climate_Risk_Disaster_Management

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook Week1.ipynb   # For Week 1
jupyter notebook Week2.ipynb   # For Week 2
```

---

## 👩‍💻 Author  
**Sharika Rajan**  
AICTE Cycle 3 (2025) Participant  
