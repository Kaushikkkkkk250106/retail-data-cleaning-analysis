<h1 align="center">🛒 Retail Data Cleaning & Analysis</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=for-the-badge&logo=pandas" alt="Pandas">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter" alt="Jupyter">
</p>

<p align="center">
  Data cleaning, preparation, and exploratory data analysis (EDA) on real-world retail
  transaction data — built with Python & Pandas as a hands-on data wrangling exercise.
</p>

---

## 📖 Overview

This project takes raw, messy retail transaction data and walks through a complete
data-wrangling pipeline — from merging disparate CSV files to a clean, analysis-ready
dataset, culminating in business-relevant insights.

It's designed as a practical demonstration of core data cleaning skills every data
analyst / data scientist needs: merging datasets, handling missing values, fixing data
types, detecting outliers, and engineering useful features.

---

## 📂 Dataset

| File | Description |
|---|---|
| `Retail_Data_Transactions.csv` | Customer transaction records — `customer_id`, `date`, `amount` |
| `Retail_Data_Response.csv` | Customer response / campaign engagement data |

---

## 🔧 What's Covered

- 🔗 **Merging datasets** — joining transactions and response data on `customer_id`
- 🔍 **Initial exploration** — data types, shape, and summary statistics
- 🧹 **Handling missing values** — identifying and treating nulls
- 🔄 **Type conversion** — parsing dates, casting integers
- 📉 **Outlier detection** — using the **Z-Score method** to flag anomalous transactions
- 🏗️ **Feature engineering** — extracting `month` from transaction dates
- 💡 **Business insights**
  - Top 3 months by total transaction amount
  - Top 5 customers by number of orders

---

## 🛠️ Tools & Libraries

| Category | Tools |
|---|---|
| **Language** | Python |
| **Data Handling** | Pandas, NumPy |
| **Statistics** | SciPy (Z-score outlier detection) |
| **Visualization** | Matplotlib, Seaborn |
| **Environment** | Jupyter Notebook |

---

## 📁 Project Structure

```
retail-data-cleaning-analysis/
├── Data_cleaning__Preparation__lyst7989.ipynb   # Main analysis notebook
├── Retail_Data_Transactions.csv                 # Transaction dataset
├── Retail_Data_Response.csv                     # Customer response dataset
└── README.md
```

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/Kaushikkkkkk250106/retail-data-cleaning-analysis.git
cd retail-data-cleaning-analysis

# (Optional) create a virtual environment
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate

# Install dependencies
pip install pandas numpy scipy matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook Data_cleaning__Preparation__lyst7989.ipynb
```

---

## 📊 Key Takeaways

Hands-on practice cleaning and preparing real retail data — building a solid,
analysis-ready foundation that can feed directly into further EDA, dashboards, or
machine learning pipelines.

---

## 🏷️ Topics

`python` `pandas` `numpy` `eda` `seaborn` `data-analysis` `beginner`

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">
Built by <b>Kaushik Tripathi</b> | Data Analytics Enthusiast<br>
Made with ❤️ and Pandas 🐼
</p>
