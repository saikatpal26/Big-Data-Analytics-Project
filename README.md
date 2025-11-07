# 🧠 Big Data Analytics using PySpark & Machine Learning  

This project demonstrates **big data analytics** and **machine learning** using **PySpark** on the **IDS 2018 Intrusion Detection Dataset** (from Kaggle).  
The entire workflow is implemented in **Google Colab** using a **Jupyter Notebook (.ipynb)** file.  

---

## 📂 Dataset  

**Source:** [IDS 2018 Intrusion Detection Dataset (Kaggle)](https://www.kaggle.com/datasets/solarmainframe/ids-intrusion-csv)  
**Format:** CSV files  
**Description:** Network intrusion data used to identify normal and malicious network traffic patterns.  

---

## ⚙️ Environment & Tools  

- **Platform:** Google Colab  
- **Language:** Python  
- **Framework:** PySpark (Spark SQL, MLlib)  
- **Notebook Type:** Jupyter (.ipynb)  

**Libraries Used:**  
`pyspark`, `pandas`, `numpy`, `matplotlib.pyplot`, `seaborn`, and other supporting modules for data analysis, visualization, and machine learning.  

---

## 🧩 Project Structure  

### **Task 1: Spark SQL Analysis**  
Performed exploratory and analytical queries using **Spark SQL**.  

**Queries and Functions Used:**  
1. Use of `COALESCE`, `COUNT`, `CASE...WHEN...THEN...END`, and `GROUP BY` clauses.  
2. Measurement of **skewness** and **kurtosis** for data distribution understanding.  
3. Data analysis and visualization queries including:  
   - Counting **normal** vs **harmful** connections.  
   - Categorizing attacks as **Network Attack** or **Database Attack** based on attack names.  
   - Querying each **attack name** with its **attacked port** and **number of attacks** (excluding *Benign*).  
