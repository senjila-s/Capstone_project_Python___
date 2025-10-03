# Capstone Project - Global Student Migration

## 📌 Project Overview
This project analyzes student migration, course enrollment, and graduation patterns using a raw dataset.  
The workflow includes data cleaning, exploratory data analysis (EDA), and interactive visualizations.

## 🛠️ Tech Stack
- Python (Pandas, NumPy)
- Plotly (interactive visualizations)
- Matplotlib / Seaborn (static visuals)
- Jupyter Notebook

## 📂 Dataset
- Contains student demographic, academic, and migration details.
- ~5000+ rows with multiple categorical and numerical features.
- Includes intentional dirtiness (missing values, duplicates, inconsistent formats).

## 🔎 Workflow
1. **Data Loading & Inspection**  
   - Load CSV into Pandas.  
   - Check column names, data types, and missing values.  

2. **Data Cleaning**  
   - Handle missing values (imputation/removal).  
   - Convert data types (e.g., `Student_Id` to integer).  
   - Remove duplicates.  
   - Standardize categorical values (university names, courses).  

3. **Exploratory Data Analysis (EDA)**  
   - Univariate analysis (distribution of students, courses, universities).  
   - Bivariate analysis (student migration by year, gender vs. course).  
   - Multivariate analysis (graduation trends across universities).
   - correlation map ( strong positive or negative relationships) 

4. **Visualizations (Interactive)**  
   - Line charts (Graduation trends by course & year).  
   - Bar charts (Student counts by university).  
   - Pie charts (Enrollment distribution).  
   - Heatmaps (Correlation between features).  
   - Sunburst/Treemap (Migration patterns).  

5. **Findings & Insights**  
   - Clear trends in student migration over the years.  
   - Popular courses and top universities identified.  
   - Data inconsistencies fixed to improve reliability.  

## 📊 Example Output
- Interactive line chart of graduation counts by course.  
- University-wise student enrollment breakdown.  
- Migration patterns across states and years.  





