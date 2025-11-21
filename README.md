# 🌸 Iris Flower Classification 

## 📝 Project Overview
This project focuses on classifying **Iris flowers** into three species:  
- Setosa  
- Versicolor  
- Virginica  

Using the classic **Iris dataset**, the project demonstrates a full **machine learning pipeline** from data exploration to modeling and evaluation.

---

## 📊 Dataset
- **Source:** Iris dataset (150 samples, 6 columns)  
- **Columns:** `Id`, `SepalLengthCm`, `SepalWidthCm`, `PetalLengthCm`, `PetalWidthCm`, `Species`  
- **Target:** `Species` (categorical)  
- **Features:** 4 numeric columns (Sepal & Petal dimensions)  
- **Balanced Classes:** 50 samples per species  
- **No missing values** ✅  

---

## 🔍 Exploratory Data Analysis (EDA)
- Checked dataset shape, missing values, duplicates, and basic statistics.  
- Visualized distributions using **histograms, KDE plots, and boxplots**.  
- Identified minor outliers in `SepalWidthCm`.  
- Examined feature relationships via **correlation heatmap**.  
- Observed distinct patterns for each feature per species, especially petal dimensions.

---

## 🧠 Modeling
- **Algorithm:** Support Vector Machine (SVM) with RBF kernel  
- **Preprocessing:**  
  - Label encoding for target  
  - Feature scaling using StandardScaler  
- **Training & Evaluation:**  
  - Split: 70% train, 30% test  
  - Metrics: Accuracy, Confusion Matrix, Classification Report  
- **Results:**  
  - Accuracy: **95.6%** ✅  
  - Minor misclassification for Versicolor  
  - Excellent precision, recall, and F1-scores for all classes  

---

## 🔹 Key Takeaways
- Petal features are highly discriminative; Sepal features provide additional information  
- SVM effectively separates Iris species with minimal errors  
- The dataset is clean, balanced, and suitable for classification tasks  
- Provides a clear example of **end-to-end machine learning workflow**

---


