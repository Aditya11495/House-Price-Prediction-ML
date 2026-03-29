House-Price-Prediction-ML/
│
├── data/
│   └── cleaned_data.csv
│
├── notebook/
│   └── house_price_analysis.ipynb
│
├── model/
│   └── house_model.pkl
│
├── app.py
├── requirements.txt
├── README.md
# 🏠 House Price Prediction using Machine Learning

# Problem Statement

The goal of this project is to predict house prices based on various features such as area, number of bedrooms, bathrooms, and floors.

# Dataset

* Contains housing-related features
* Cleaned by handling missing values, outliers, and incorrect entries


# Steps Performed

* Data Cleaning (fixed invalid values like floors)
* Feature Selection
* Outlier Removal
* Model Training (Linear Regression)
* Model Evaluation

---

# Model Performance

* R² Score: **0.89**
* Model performs well on test data with minimal overfitting

---

## 📊 Visualizations

* Actual vs Predicted Plot
* Residual Plot
* Error Distribution

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
```

```bash
python app.py
```

---

## 🧠 Key Learnings

* Importance of data cleaning
* Feature consistency during training & testing
* Model evaluation using multiple metrics

---

## 📌 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Add web interface (Streamlit)
* Improve feature engineering

---

## 👨‍💻 Author

Aditya Singh
