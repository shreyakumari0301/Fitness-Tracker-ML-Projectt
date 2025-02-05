# Fitness Tracker - Machine Learning Model

This repository contains the Machine Learning model for predicting and analyzing fitness-related metrics using a **Fitness Tracker** dataset. The model is built using Python and common ML libraries such as `pandas`, `numpy`, `scikit-learn`, and `matplotlib`.

## 📌 Features
- Data preprocessing (handling missing values, encoding categorical features, and scaling)
- Outlier detection and removal
- Feature selection
- Model training and evaluation
- Performance metrics analysis

## 📂 Dataset
The dataset contains information about different fitness trackers, including pricing, ratings, and product specifications. Below are the key columns:

| Column Name            | Description |
|------------------------|-------------|
| **Brand**             | Brand of the fitness tracker |
| **Current Price**     | Price at the time of scraping |
| **Original Price**    | Price at the time of launch |
| **Discount Percentage** | Discount available as of now |
| **Rating**           | Product rating given by customers |
| **Number of Ratings** | Number of ratings received by the product |
| **Model Name**       | Specific model name under the brand |
| **Dial Shape**       | Shape of the dial (e.g., circular, square) |
| **Strap Color**      | Color of the strap |

### 🔹 Preprocessing Steps:
1. **Handling Missing Values**: Imputed missing values using mean/median for numerical data and mode for categorical data.
2. **Outlier Removal**: Used **IQR method** to remove extreme values.
3. **Feature Scaling**: Applied **MinMaxScaler** to normalize numerical features.
4. **Categorical Encoding**: Used **One-Hot Encoding** for categorical columns.

## 🏋️‍♂️ Model Training
We trained multiple baseline models and compared their performance:
- **Logistic Regression**
- **Random Forest**
- **XGBoost**

### 📊 Model Evaluation
The models were evaluated using the following metrics:
- Accuracy
- Precision, r2 score
