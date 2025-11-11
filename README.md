# Exploratory Data Analysis (EDA) Cardiographic Dataset

This project performs an in-depth **Exploratory Data Analysis (EDA)** on a **Cardiotocographic (CTG) dataset** to explore fetal health patterns and relationships among physiological parameters.  
It demonstrates a complete data analysis workflow from **data cleaning** to **statistical interpretation** and **visual insights**.

---

## 🧩 Objectives
- Clean and preprocess the dataset for analysis.  
- Identify missing values, duplicates, and outliers.  
- Visualize variable distributions and correlations.  
- Derive actionable insights from the statistical patterns.

---

## 🧰 Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  

---

## ⚙️ Key Steps

1. **Data Loading & Inspection**  
   - Reads the dataset and displays structure, info, and column types.

2. **Data Cleaning**  
   - Handles missing values using median imputation.  
   - Removes duplicates and validates data types.

3. **Outlier Detection**  
   - Uses Z-score and IQR methods for identifying extreme values.

4. **Descriptive Statistics**  
   - Generates statistical summaries (mean, median, std, IQR).

5. **Visual Analysis**  
   - **Histograms** — variable distribution  
   - **Boxplots & Violin Plots** — outlier visualization  
   - **Correlation Heatmap** — feature relationships  
   - **Pairplot** — multivariate relationships  

6. **Pattern Recognition**  
   - Detects strong positive and negative correlations (> 0.7 or < -0.7).  
   - Highlights potentially predictive features.

---

## 📊 Insights & Observations

✔ Dataset is clean and balanced with minimal missing values.  
✔ Visualizations reveal strong relationships among LB, ASTV, and ALTV.  
✔ Several mild outliers observed in fetal heart rate metrics.  
✔ Correlation heatmap and pairplot provide clarity on variable interactions.  
✔ Findings support feature selection for future predictive modeling.

