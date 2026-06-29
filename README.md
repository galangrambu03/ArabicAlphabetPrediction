# 🚀 Arabic Character Recognition using Decision Tree Algorithm

## 📌 Overview
This project focuses on classifying and predicting **handwritten Arabic (Hijaiyah) characters** from image extraction data using **Machine Learning**. 

The dataset contains thousands of handwritten Arabic character samples that have been preprocessed and converted into numerical tabular features. By applying a **Decision Tree classification model**, this project automatically recognizes and distinguishes different characters based on their visual patterns.

The ultimate goal is to understand dataset patterns, build an accurate classification model, and deploy it through a user-friendly interface.

---

## 📊 Dataset Information
* **Dataset Size:** Around 16,800 images of handwritten Arabic characters.
* **Format:** Extracted image data transformed into numeric/tabular features.
* **Image Specifications:** Each original character image was preprocessed to a uniform size of **32 × 32 pixels** before feature extraction.
* **Target Classes:** Various Arabic/Hijaiyah letters.

---

## 🎯 Objectives
1. **Explore and Understand Data:** Analyze the patterns, structures, and information within the extracted feature dataset.
2. **Develop AI Model:** Build a robust Machine Learning model capable of accurately classifying and differentiating Arabic characters.
3. **Deploy GUI Application:** Build a simple and interactive Graphical User Interface (GUI) that allows users to input data and get real-time character predictions.

---

## ⚙️ Methodology

### 1. Exploratory Data Analysis (EDA)
* Inspect dataset structure and feature dimensions.
* Analyze descriptive statistics to check data scales, dispersions, and missing values.
* Understand feature characteristics before feeding them into the model.

### 2. Data Preprocessing & Feature Engineering
* Prepare numerical tabular data from the image extraction results.
* Ensure data alignment for the classification model.

### 3. Classification (Supervised Learning)
* **Algorithm:** Decision Tree Classifier
* **Goal:** Learn decision boundaries from the 32x32 pixel extracted features to predict the correct Hijaiyah letter.

### 4. Graphical User Interface (GUI)
* Developed using **Tkinter**.
* Allows users to paste a single row of extracted image feature data to get an instant, real-time prediction of the Arabic character.

---

## 🧠 Key Features
* Automated multi-class classification for handwritten Arabic characters.
* Full End-to-End ML pipeline (EDA, Preprocessing, Model Training, and Evaluation).
* Interactive and lightweight Tkinter GUI for real-time inference.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Machine Learning & Data Analysis:** Pandas, NumPy, Scikit-Learn
* **Visualization:** Matplotlib, Seaborn
* **Interface:** Tkinter
* **Environment:** Jupyter Notebook

---

## 🚀 How to Run

```bash
# 1. Clone this repository
git clone [https://github.com/galangrambu03/ArabicAlphabetPrediction.git](https://github.com/galangrambu03/ArabicAlphabetPrediction.git)

# 2. Go to the project directory
cd ArabicAlphabetPrediction

# 3. Install required libraries
pip install pandas numpy scikit-learn matplotlib seaborn

# 4. Launch Jupyter Notebook to see the model training
jupyter notebook
