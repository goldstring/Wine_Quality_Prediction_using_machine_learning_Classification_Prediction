# 🍷 Wine Quality Classification using Machine Learning

This project aims to predict the quality of wine samples based on various physicochemical attributes using multiple machine learning models. 
The dataset is sourced from the UCI Machine Learning Repository and contains chemical analysis data of red and white wine variants.

---

## 📌 Project Objective

To build and evaluate machine learning classification models that can categorize wine quality into multiple classes (typically low, medium, high),
using chemical attributes as input features.

---

## 🧾 Dataset Details

- **Source:** [Wine Quality Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
- **Records:** ~1600 (for red wine)
- **Type:** Multiclass classification

### 🔍 Features

| Feature Name             | Description                                      |
|--------------------------|--------------------------------------------------|
| fixed acidity            | Tartaric acid content (g/dm³)                   |
| volatile acidity         | Acetic acid content (g/dm³)                     |
| citric acid              | Citric acid content (g/dm³)                     |
| residual sugar           | Sugar left after fermentation (g/dm³)          |
| chlorides                | Salt content (g/dm³)                            |
| free sulfur dioxide      | SO₂ that protects against microbes (mg/dm³)     |
| total sulfur dioxide     | Total SO₂ (mg/dm³)                              |
| density                  | Wine density (g/cm³)                            |
| pH                       | Acidity level                                   |
| sulphates                | Sulfate level, wine preservative (g/dm³)        |
| alcohol                  | Alcohol content (% vol)                         |

### 🎯 Target

- `quality`: Integer score between 0 and 10 (usually 3 to 8)
- Commonly grouped into:  
  - **Low Quality**: 3–4  
  - **Medium Quality**: 5–6  
  - **High Quality**: 7–8

---

## 🧠 ML Models Used

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Decision Tree

---

## ⚙️ Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- TensorFlow / Keras for ANN
- Jupyter Notebook / Colab

---

## 📊 Evaluation Metrics

- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- Cross-validation

---



