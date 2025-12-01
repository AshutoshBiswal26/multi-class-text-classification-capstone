# 🚀 Multi-Class Text Classification Capstone Project
**End-to-End NLP Pipeline using Python 3.11, TF-IDF Vectorization, and Logistic Regression**

This repository contains a complete machine learning workflow for **multi-class text classification**, including preprocessing, feature extraction, model training, evaluation, and prediction on new text data. The project is built as part of a **capstone requirement**, and follows clean modular design suitable for academic submission or real-world extension.

---

## 📘 Project Overview

This project demonstrates how to build an NLP-based classification system using traditional machine learning. Given a text input, the model predicts one of several categories (e.g., *tech*, *sports*, *politics*).

The project includes:

- Text preprocessing
- TF-IDF vectorization
- Logistic Regression classifier
- Model evaluation (accuracy, precision, recall, F1-score)
- Prediction on unseen text

---

## 🎯 Problem Statement

Text data is unstructured and requires cleaning and transformation before use in machine learning.  
This project focuses on:

- Converting text into usable numerical features  
- Training a classifier for multi-class categorization  
- Generating insights from model performance  
- Making real-time predictions on new text  

---

## 🗂️ Dataset

A small example dataset is included directly in code for demonstration.  
It can be easily replaced with any real-world dataset for more advanced use cases.

Labels include:
- **Tech**
- **Sports**
- **Politics**

---

## 🧠 Methodology

### 🔹 1. Text Preprocessing
- Lowercasing  
- Removing special characters  
- Basic text cleaning  

### 🔹 2. Vectorization (TF-IDF)
Using `TfidfVectorizer` from `scikit-learn`.

### 🔹 3. Model Training
The model used:
- **Logistic Regression** (multi-class)

### 🔹 4. Model Evaluation
Metrics include:
- Accuracy  
- Precision, Recall, F1-score  

### 🔹 5. Predicting New Text
A helper function allows classification on any input sentence.




