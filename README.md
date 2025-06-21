# -Olist-Ecommerce-EDA-Python-Analysis
End-to-end EDA of Brazilian e-commerce dataset using Python &amp; Pandas.
# 🛍️ Olist E-Commerce Data Analysis (Python EDA)

This project presents an end-to-end exploratory data analysis (EDA) of the Brazilian Olist e-commerce dataset using Python. The analysis focuses on customer behavior, delivery performance, profitability, and product trends.

## 📌 Objective

To uncover key business insights from raw e-commerce data using Python tools like Pandas, Seaborn, and Matplotlib.

---

## 📁 Dataset Overview

The project uses the following files (stored in `data/` folder):

| File Name         | Description |
|-------------------|-------------|
| `customers.csv`   | Customer IDs, location info |
| `orders.csv`      | Order status & timestamps |
| `order_items.csv` | Items per order (product & price) |
| `products.csv`    | Product categories & dimensions |
| `sellers.csv`     | Seller info |
| `payments.csv`    | Payment type, value |
| `reviews.csv`     | Review scores & comments |

---

## 🔍 Key Insights

### 📦 Delivery Performance
- **Average delivery time** is ~12.2 days
- Some products are delayed beyond expected delivery

### 💰 Profitability
- Freight cost significantly reduces profit margin in some categories
- High-value products often have low relative margins

### 🧑‍🤝‍🧑 Customer Behavior
- ~15% customers are repeat buyers
- Most customers are located in major cities (São Paulo, Rio)

### 🛍️ Product & Review Analysis
- Most sold categories: **bed_bath_table**, **health_beauty**
- Review scores skew positively (avg. ~4.1)

---

## 📊 Tools Used

- Python 3.x
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Project Structure
Olist_EDA_Python_Project/
├── Olist_Ecommerce_EDA.ipynb ← main notebook
├── Insight Report
└── README.md

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/Olist-EDA-Python.git
   cd Olist-EDA-Python
pip install -r requirements.txt
jupyter notebook

 Acknowledgements
Data is sourced from the Brazilian Olist E-commerce Dataset.
Contact
Name: Your Name

Email: anwarkhanmothuka@gamil.com

LinkedIn: linkedin.com/in/yourprofile
