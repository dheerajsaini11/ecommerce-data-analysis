# 🛒 E-Commerce Data Analysis Project

## 📌 Project Overview

This project analyzes a large-scale e-commerce dataset to uncover insights related to pricing, sales trends, and customer behavior. The goal is to perform end-to-end data analysis including data cleaning, exploration, and visualization.

---

## 🎯 Objectives

* Understand sales trends over time
* Analyze price distribution across products
* Identify top-performing brands
* Explore factors affecting product pricing

---

## 🗂️ Project Structure

```
ecommerce-data-analysis/
│
├── data/
│   ├── raw/            # Original dataset
│   └── processed/      # Cleaned dataset
│
├── notebooks/          # Jupyter notebooks (EDA & analysis)
├── src/                # Python scripts (future use)
├── outputs/            # Charts and reports
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🧹 Data Cleaning Steps

* Removed rows with missing target values (`sellingprice`)
* Handled missing categorical values using "Unknown"
* Filled numerical missing values using median
* Fixed invalid date formats and timezone inconsistencies
* Converted `saledate` to datetime format

---

## 📊 Key Insights (To Be Expanded)

* High mileage vehicles tend to have lower selling prices
* Certain brands dominate the market in volume
* Pricing varies significantly across vehicle types
* Seasonal trends observed in vehicle sales

---

## 🛠️ Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Jupyter Notebook
* Git & GitHub

---

## 🚀 How to Run This Project

```bash
git clone https://github.com/dheerajsaini11/ecommerce-data-analysis.git
cd ecommerce-data-analysis
pip install -r requirements.txt
```

---

## 📌 Future Improvements

* Build interactive dashboard (Streamlit / Power BI)
* Add machine learning model for price prediction
* Deploy as web app

---

## 👤 Author

Dheeraj Saini
