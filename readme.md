# **Student Performance Prediction — Machine Learning Project**

📘 *A data-driven approach to predict student academic performance using machine learning techniques.*

---

# **Project Overview**

This project aims to predict whether a student will **Pass** or **Fail** based on academic, demographic, and behavioral features.
Using machine learning models, educational institutions can:

* Identify at-risk students early
* Provide timely interventions
* Improve academic outcomes
* Make data-informed decisions

The project includes **EDA, preprocessing, model comparison, and evaluation**—following a complete machine learning workflow.

---

## **Project Structure**

```
📁 student-performance-prediction
│
├── 📄 student_performance_dataset.csv
├── 📄 student_performance_prediction.ipynb
├── 📄 README.md
│
└── 📁 outputs/
    ├── accuracy_comparison.png
    ├── confusion_matrix_best_model.png
    └── eda_visuals/
```

---

## **Key Features**

✔ Full Exploratory Data Analysis (EDA)
✔ Missing value handling
✔ Outlier detection
✔ Feature scaling (Standardization)
✔ One-hot encoding for categorical features
✔ Train-test split with stratification
✔ **Four machine learning models trained:**

* Logistic Regression
* Random Forest
* Gradient Boosting Classifir
* K-Nearest Neighbors

✔ Model evaluation using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
  
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/94baa8f9-0d62-4d43-9e2d-f594ae78db11" />

✔ Model comparison using a bar chart
✔ Identification of *best-performing model*

---

## **Dataset**

The dataset contains **708** student records with the following feature categories:

### 🔹 Academic Attributes

* Past Exam Scores
* Attendance Rate
* Study Hours per Week

### 🔹 Demographic & Socioeconomic

* Gender
* Parental Education
* Internet Access

### 🎯 **Target Variable:** `Pass_Fail`

---

## **Exploratory Data Analysis (EDA)**

The notebook includes visualizations such as:

* Histograms
* Bar Charts
* Pie Chart
* Correlation Heatmap
* Boxplots

These helped uncover key insights:

📌 Higher attendance and past exam scores strongly correlate with passing
📌 Study hours significantly impact final outcomes
📌 Some categorical features show imbalance

---

## **Technologies Used**

* Python
* Pandas, NumPy
* Scikit-Learn
* Matplotlib, Seaborn
* Jupyter Notebook / Google Colab

---

## **Modeling & Evaluation**

Six models were trained and evaluated.
Below is a summary of their performance (sample template):

| Model                  | Accuracy |
| ---------------------- | -------- |
| Logistic Regression    | 92%      |
| Random Forest          | 100%     |
| Gradient Boosting      | 100%     |
| KNN                    | 75%      |

### **Best Model: Random Forest Classifier**

* Highest accuracy
* Balanced precision and recall
* Excellent confusion matrix performance

---

## **Key Insights**

* Attendance Rate is one of the strongest predictors of performance
* Past exam results provide clear indication of student outcomes
* Study habits have measurable influence on success
* Socioeconomic factors contribute moderately

---

## **Future Improvements**

* Introduce deep learning models for enhanced prediction
* Collect more diverse data from multiple institutions
* Build a student performance monitoring dashboard
* Deploy as a web or mobile application

---

## **How to Run the Project**

### **1️⃣ Clone the repository**

```bash
git clone https://github.com/yourusername/student-performance-prediction.git
cd student-performance-prediction
```

### **2️⃣ Install dependencies**

```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Jupyter Notebook**

```bash
jupyter notebook student_performance_prediction.ipynb
```

Or open it directly in **Google Colab**.

---

## **Author**

[Niyaz Ahmad Khan](https://www.linkedin.com/in/theniyazkhan/)
[Eshrath Jahan Esha](https://www.linkedin.com/in/eshrath-esha-250b95282)


---

##  **If you found this useful, consider giving the repository a star!**

---
