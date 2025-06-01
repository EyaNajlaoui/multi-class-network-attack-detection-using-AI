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

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Loss & accuracy curves

