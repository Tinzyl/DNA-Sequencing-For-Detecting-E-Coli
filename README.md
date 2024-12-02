# DNA Sequencing for Detecting E. Coli

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)  
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Support%20Vector%20Machine-orange.svg)  
![Status](https://img.shields.io/badge/Status-Complete-brightgreen.svg)  

## Project Description 📜
This project classifies DNA sequences as promoters or non-promoters to detect E. Coli. Using the UCI Promoter Gene Sequences dataset, the system implements machine learning techniques for binary classification with a focus on simplicity and accuracy.

---

## Key Features ✨
- **Data Preprocessing**: Converts DNA sequences into numeric matrices for machine learning.
- **Machine Learning**: Uses a Support Vector Machine (SVM) for classification.
- **Performance Metrics**: Confusion matrix and loss curve analysis.

---

**Machine Learning Workflow 🧬**

Preprocessing: Converts DNA sequences to a numeric format using one-hot encoding.

Model Training: Trains an SVM on processed data.

Model Evaluation: Outputs metrics like confusion matrix and loss curves.

---

**Results** 📊

**Confusion Matrix:**
|----------------------------|
|         Predicted|:        |
|        Positive  Negative  |
|Actual:                     |
| Positive   15       0      |
| Negative    2      10      |
|                            |
------------------------------
