# 🛡️ Multi-Class Network Attack Classification using Machine Learning and Deep Learning

This repository contains my **Final Year Project (PFA 2)** for the Applied Mathematics and Modeling Engineering program at ENSIT. The goal of the project is to classify different types of **network attacks** using both **Machine Learning (ML)** and **Deep Learning (DL)** techniques.

---

## 🎯 Project Objective

To build and evaluate supervised models capable of classifying network traffic into **six different attack categories**, in addition to normal traffic. This work contributes to enhancing the efficiency of **cybersecurity systems** by automating attack detection using Artificial Intelligence.

---

## 🧠 Models Used

### ✅ Machine Learning:
- **Random Forest (RF)**
- **Gaussian Naive Bayes (GNB)**

### ✅ Deep Learning:
- **Long Short-Term Memory (LSTM)**

---

## 📊 Attack Categories

The models are trained to classify the following types of traffic:

- **DoS** (Denial of Service)
- **PortScan**
- **Brute Force**
- **Bot**
- **Web Attacks**
- **Infiltration**
- **Normal Traffic**

---

## 🧹 Data Preprocessing

- Cleaning missing and infinite values
- Label encoding of categorical features
- Normalization of numeric features
- **Balancing the dataset** using:
  - **SMOTE** (Synthetic Minority Over-sampling Technique)
  - **Random under-sampling**
- Splitting into training and test sets

---
# ⚙️ Hyperparameter Optimization

To maximize model performance and address overfitting caused by the dataset’s severe class imbalance (~80% normal traffic), I optimized hyperparameters for all models using manual tuning and random search techniques. This process significantly improved accuracy, achieving 94% for ML models (Random Forest, Gaussian Naive Bayes) and 81% for LSTM.

# --- Techniques Used ---

# - Manual Tuning:
 - Iteratively adjusted parameters based on validation performance to find optimal configurations, balancing model complexity and generalization.

# --- Model-Specific Optimizations ---

# - Random Forest:
Tuned parameters such as n_estimators , max_depth , and min_samples_split to control tree complexity and prevent overfitting. 

# - Gaussian Naive Bayes:
Adjusted var_smoothing to stabilize probability estimates, improving performance on imbalanced classes.

# - LSTM:
Optimized architecture parameters like number of layers, units per layer , and dropout rate , as well as training parameters like learning rate and batch size .

# --- Outcome ---

# Hyperparameter optimization mitigated overfitting and improved recall
# for minority classes (e.g., Brute Force, Infiltration).
# Resulted in robust performance across all attack categories.
---
## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Loss & accuracy curves
---
## 🛠️ Tools and Libraries
- Programming Language: Python
- Data Processing: Pandas, NumPy
- Visualization: Matplotlib, Seaborn
- Machine Learning: scikit-learn, imbalanced-learn (for SMOTE)
- Deep Learning: TensorFlow, Keras
- Version Control: Git, GitHub
- Documentation: Jupyter Notebook
---
##  📊 Results
- Machine Learning Models: Achieved 94% accuracy with Random Forest and Gaussian Naive Bayes, excelling in balanced class detection after SMOTE and undersampling.
- Deep Learning Model: LSTM reached 81% accuracy, effectively capturing temporal patterns in network traffic.
- Minority Class Detection: Improved recall for rare attacks (e.g., Infiltration, Web Attacks) through data balancing and hyperparameter tuning.
- Visualizations: Confusion matrices and loss/accuracy curves are available in the notebook for detailed performance analysis.
