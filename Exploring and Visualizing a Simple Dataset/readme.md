# 🌸 Iris Flower Classification Project

## 📌 Project Overview
This project focuses on the classic **Iris dataset** to perform Exploratory Data Analysis (EDA) and species classification. The notebook demonstrates the complete machine learning workflow, from data loading to visualization and statistical summary.

---

## 🎯 Task Objective
The primary goal is to classify Iris flowers into three species (**Setosa, Versicolor, Virginica**) based on their physical measurements. The objectives include:

- Python-based data manipulation  
- Exploratory Data Analysis (EDA) using statistical methods  
- Data visualization to identify patterns and class separability  

---

## 📊 Dataset Used
- Dataset: **Iris Flower Dataset (Fisher’s Iris dataset)**  
- Source: Loaded directly via the **seaborn** library  
- Total Samples: 150 instances  

### Features:
- `sepal_length` (cm)  
- `sepal_width` (cm)  
- `petal_length` (cm)  
- `petal_width` (cm)  

- **Target Variable:** `species` (Setosa, Versicolor, Virginica)

---

## ⚙️ Models and Libraries Applied
- **Data Handling:** `pandas`, `numpy`  
- **Visualization:** `matplotlib.pyplot`, `seaborn`  
- **Methodology:**  
  - Statistical Analysis: `df.describe()`, `df.info()` to understand data distribution and check for null values  
  - Visual Inspection: Scatter plots to analyze the relationship between sepal and petal dimensions  

---

## 📈 Key Results & Findings
- **Class Separability:** Scatter plots (Sepal Length vs. Petal Length) show that **Iris-setosa** is linearly separable from other species  
- **Data Integrity:** Dataset is clean with 0 null values  
- **Feature Correlation:** Petal measurements (length and width) vary more between species than sepal measurements, making them more influential for classification  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📂 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/iris-flower-classification.git