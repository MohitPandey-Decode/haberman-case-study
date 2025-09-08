# haberman-case-study
Python case study on Haberman's survival dataset with EDA and visualization.
# 📊 Haberman Survival Dataset - Exploratory Data Analysis (EDA)

## 🔹 Project Overview
This project is based on the **Haberman’s Survival Dataset**, which contains the survival records of patients who had undergone surgery for breast cancer at the University of Chicago's Billings Hospital between 1958 and 1970.  

The main objective of this case study is to analyze whether factors such as **Age**, **Year of Operation**, and **Number of Positive Axillary Nodes** have an impact on the **survival status** of patients after 5 years.

---

## 🔹 Problem Statement
> Given the age of the patient, year of operation, and the number of positive lymph nodes detected, analyze and visualize patterns that help us understand the survival chances of the patient beyond 5 years.

---

## 🔹 Dataset Information
- **Age**: Age of patient at the time of operation (in years)  
- **Year**: Year of operation (year - 1900, e.g., 62 = 1962)  
- **Nodes**: Number of positive axillary lymph nodes detected  
- **Survival**: Patient survival status  
  - `1` = Patient survived **5 years or more** after operation  
  - `2` = Patient **died within 5 years** of operation  

---

## 🔹 Tools & Libraries Used
- **Python**  
- **NumPy**  
- **Pandas**  
- **Matplotlib**  
- **Seaborn**  

---

## 🔹 Steps Performed
1. **Data Loading** – Imported dataset and renamed columns for better understanding.  
2. **Data Exploration** – Checked dataset shape, missing values, descriptive statistics.  
3. **Class Distribution** – Checked balance of survival classes.  
4. **Visualizations**:  
   - Histogram of Age and Nodes  
   - Boxplots (Survival vs Age/Nodes)  
   - ECDF Plots with threshold lines  
   - Correlation Heatmap  
5. **Insights** – Derived meaningful conclusions from graphs.  

---

## 🔹 Key Insights
- Most patients were between **30 to 70 years** old.  
- **Survival classes are imbalanced** – more patients survived (class 1) compared to those who didn’t (class 2).  
- Patients with **higher lymph node counts** had significantly **lower chances of survival**.  
- **Age has some impact**, but **number of nodes is the strongest factor** affecting survival.  

---

## 🔹 Sample Visualizations

📌 **Age Distribution**
![Age Distribution](https://via.placeholder.com/600x300.png?text=Age+Distribution+Plot)

📌 **Survival vs Nodes**
![Nodes Boxplot](https://via.placeholder.com/600x300.png?text=Nodes+vs+Survival+Boxplot)

📌 **ECDF Plot**
![ECDF](https://via.placeholder.com/600x300.png?text=ECDF+Plot)

---

## ✅ Conclusion
This case study demonstrates how **Exploratory Data Analysis (EDA)** can provide valuable insights into medical datasets.  
Even without machine learning, we can identify **key factors (like lymph nodes)** that strongly influence patient survival chances.  

---

## 🔹 Author
👨‍💻 **Mohit Pandey**  
📍 Data Science Enthusiast | Python | SQL | Pandas | Visualization  

---

⭐ If you found this project insightful, feel free to star ⭐ the repo!
