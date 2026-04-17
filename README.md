# 🤖 How AI is Changing Student Life (2026)

## 📌 Project Overview

This project analyzes how Artificial Intelligence (AI) tools are impacting student life in 2026.
Using a dataset of 1500 students, we explore how AI affects:

* 📈 Academic performance (GPA improvement)
* ⏳ Time efficiency
* 🎯 Career confidence
* ⚖️ Ethical concerns

---

## 📊 Dataset Information

The dataset contains **1500 student records** with the following features:

* `Age` – Student age
* `Major` – Field of study
* `Primary_AI_Tool` – Most used AI tool
* `Task_Frequency_Daily` – Daily AI usage frequency
* `Main_Usage_Case` – Purpose of AI usage
* `GPA_Baseline` – GPA before AI usage
* `GPA_Post_AI` – GPA after AI usage
* `Time_Saved_Hours_Weekly` – Weekly time saved
* `AI_Ethics_Concern` – Ethical concerns about AI
* `Career_Confidence_Score` – Confidence in future career

---

## ⚙️ Data Processing

### Feature Engineering

* Created a new feature:

  * **GPA_Change = GPA_Post_AI - GPA_Baseline**
* Categorized AI usage:

  * Low / Medium / High usage levels

### Data Preparation

* Encoded categorical variables using:

  * Label Encoding
  * One-Hot Encoding (alternative)

---

## 📈 Exploratory Data Analysis (EDA)

The following visualizations were used:

* Histogram → GPA Change distribution
* Boxplot → AI usage vs GPA improvement
* Bar Chart → Most used AI tools
* Pie Chart → AI usage purposes
* Heatmap → Feature correlations

---

## 🔍 Key Insights

* 📈 Most students experienced an **increase in GPA** after using AI tools
* 🔥 Higher AI usage is associated with **greater academic improvement**
* ⏳ Students save a significant amount of time weekly using AI
* 🎯 AI usage positively correlates with **career confidence**
* ⚖️ Ethical concerns may slightly reduce AI effectiveness

---

## 🤖 Machine Learning Model

A **Random Forest Regressor** was used to predict GPA improvement.

### Steps:

* Data splitting (80% train / 20% test)
* Model training
* Performance evaluation

### Result:

* The model successfully captures relationships between AI usage and academic performance

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📎 Conclusion

AI is significantly transforming student life by improving efficiency, academic performance, and career confidence. However, ethical concerns remain an important factor influencing AI adoption and effectiveness.

---

## 👩‍💻 Author

Gizem Sena ÇENGEL
Computer Engineer
AI & Data Science Enthusiast 🚀
