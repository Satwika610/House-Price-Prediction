# 🏠 House Price Prediction using Machine Learning

## 📌 Internship Details

- **Name:** Satwika Guda
- **Intern ID:** CITS8100
- **Organization:** CodTech IT Solutions Private Limited
- **Domain:** Artificial Intelligence
- **Internship Duration:** 6 Weeks
- **Internship Period:** 01 August 2026 – 12 September 2026

---

## 📖 Project Overview

This project aims to predict house prices using a **Machine Learning Linear Regression model**. The model is trained on a housing dataset containing various features such as bedrooms, bathrooms, living area, floors, year built, and city. After preprocessing the data, the model learns the relationship between these features and the house price, enabling it to predict the price of new houses.

---

## 🎯 Objective

- Predict house prices based on house features.
- Perform data preprocessing and feature engineering.
- Train a Linear Regression model.
- Evaluate the model using standard regression metrics.

---

## 📂 Dataset Information

- **Dataset:** House Sales Dataset
- **Total Records:** 4600
- **Total Features:** 18

### Dataset Features

- Date
- Bedrooms
- Bathrooms
- Living Area (sqft)
- Lot Area (sqft)
- Floors
- Waterfront
- View
- Condition
- Sqft Above
- Sqft Basement
- Year Built
- Year Renovated
- City
- Price (Target Variable)

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- GitHub

---

## 🤖 Machine Learning Model

- Linear Regression

---

## 🔍 Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Handle Missing Values
5. Remove Unnecessary Columns
6. Feature Engineering
7. Convert Categorical Data using One-Hot Encoding
8. Split Dataset into Training and Testing Sets
9. Train Linear Regression Model
10. Predict House Prices
11. Evaluate Model Performance
12. Save Trained Model

---

## 📈 Model Performance

| Metric | Value |
|--------|--------|
| MAE | 131869.56 |
| RMSE | 219398.99 |
| R² Score | 0.6764 |

---

## 📊 Results

The Linear Regression model successfully predicts house prices based on the given features. The achieved **R² Score of 0.6764** indicates that the model explains approximately **67.64%** of the variation in house prices, making it a good baseline model for this dataset.

---

## 📁 Project Structure

```text
House-Price-Prediction
│
├── data
│   └── data.csv
│
├── notebook
│   └── HousePricePrediction.ipynb
│
├── model
│   └── house_price_model.pkl
│
├── images
│   ├── dataset.png
│   ├── prediction.png
│   └── evaluation.png
│
├── README.md
├── requirements.txt
└── LICENSE (Optional)
```

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/your-github-username/House-Price-Prediction.git
```

> **Note:** Replace `your-github-username` with your actual GitHub username.

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open:

```
HousePricePrediction.ipynb
```

Run all the cells in **Google Colab** or **Jupyter Notebook**.

---

## 📌 Future Improvements

- Improve prediction accuracy using advanced regression algorithms.
- Deploy the model using Streamlit.
- Add more location-based features.
- Perform hyperparameter tuning.
- Compare multiple Machine Learning models.

---

## 👩‍💻 Author

**Satwika Guda**

Artificial Intelligence Intern

CodTech IT Solutions Private Limited

---

## ⭐ Acknowledgement

This project was developed as part of the **Artificial Intelligence Internship** at **CodTech IT Solutions Private Limited**. It demonstrates the implementation of a **Linear Regression** model for predicting house prices using machine learning techniques such as data preprocessing, feature engineering, model training, and performance evaluation.
