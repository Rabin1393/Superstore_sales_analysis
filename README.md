# Smart Sales & Demand Analysis System

## Project Overview

This project analyzes sales data to uncover trends, generate business insights, and predict future demand using machine learning.

The goal is to simulate real-world data science tasks such as data cleaning, analysis, visualization, and forecasting to support business decision-making.

---

## Objectives

* Perform data cleaning and preprocessing
* Analyze sales trends across time, region, and products
* Build a machine learning model to predict future sales
* Generate actionable business insights

---

## Tech Stack

* Python (Pandas, NumPy)
* SQL (SQLite)
* Data Visualization (Matplotlib / Seaborn)
* Machine Learning (Scikit-learn)

---

## Project Structure

```
superstore_sales_analysis/
│
├── Data/
│   └── superstore.csv
│
├── sales.db
│
├── superstore_analysis.ipynb
│
└── README.md
```

---

## Dataset

* Source: https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting
* Description: Contains sales transactions including product, region, date, and revenue.

---

## Data Cleaning

* Handled missing values
* Converted date columns to proper format
* Removed duplicates
* Standardized column names

---

## Exploratory Data Analysis (EDA)

Key analysis performed:

* Monthly and yearly sales trends
* Top-performing products
* Region-wise sales comparison

---

## Machine Learning Model

* Model Used: Linear Regression / Random Forest
* Features: Date-based features, product category, region, etc.
* Target Variable: Sales

### Model Performance

* R² Score: XX
* Mean Squared Error: XX

---

## Key Business Insights

* Sales peak in November–December → increase inventory before peak season
* Top 20% of products generate majority of revenue → focus on high-performing items
* Certain regions underperform → opportunity for targeted marketing

---

## How to Run the Project

1. Clone the repository:

```
git clone https://github.com/Rabin1393/Superstore_sales_analysis
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run Jupyter Notebook:

```
jupyter notebook
```

---

## 💡 Future Improvements

* Add more advanced ML models (XGBoost, etc.)
* Deploy using Streamlit
* Use real-time data from APIs

---

## 👨‍💻 Author

* Rabin Khadka
* GitHub: https://github.com/Rabin1393 

---

## ⭐ If you found this project useful, consider giving it a star!
