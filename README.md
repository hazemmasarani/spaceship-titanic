# 🚀 Spaceship Titanic - Kaggle Competition

In the year 2912, a catastrophic event struck the interstellar passenger liner **Spaceship Titanic** during its journey across the galaxy. After colliding with a mysterious spacetime anomaly near Alpha Centauri, nearly half of the passengers were transported to an alternate dimension.

This project aims to solve this cosmic mystery using machine learning.

---

## 📌 Project Overview

The goal of this project is to build a predictive model that determines whether a passenger was **transported to another dimension** based on various features such as demographics, spending behavior, and cabin information.

This is part of the **Spaceship Titanic Kaggle Competition**, a beginner-friendly but rich dataset that requires strong data preprocessing, feature engineering, and model selection.

---

## 📊 Dataset Description

The dataset includes information about passengers such as:

- **Personal details:** Age, VIP status, Home Planet  
- **Travel details:** Cabin, Destination  
- **Spending behavior:** Room Service, Food Court, Spa, VR Deck, etc.  
- **Special conditions:** CryoSleep status  

### 🎯 Target Variable

- **Transported** → Whether the passenger was moved to another dimension (True/False)

---

## 🛠️ Approach

This project follows a complete data science pipeline:

### 1. Data Cleaning & Preprocessing
- Handling missing values using statistical and domain-based methods  
- Feature extraction from complex columns (e.g., Cabin → Deck / Number / Side)  
- Encoding categorical variables  

### 2. Feature Engineering
- Creating aggregated spending features  
- Inferring missing behavioral patterns (e.g., CryoSleep vs spending)  
- Exploring relationships between features  

### 3. Model Building
- Experimenting with multiple models including:
  - Random Forest  
  - Gradient Boosting (e.g., CatBoost)  
- Using cross-validation (K-Fold) for robust evaluation  

### 4. Evaluation
- Performance measured using classification accuracy  
- Analysis of false positives and false negatives  