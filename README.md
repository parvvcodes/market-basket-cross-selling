# 🛒 Market Basket Analysis & Product Recommendation System

A **Market Basket Analysis** project that identifies products frequently purchased together and uses those relationships to generate **product recommendations and cross-selling opportunities**.

## 📌 Project Overview

This project analyzes grocery transaction data using **Association Rule Mining**.

Two algorithms are implemented:

* **Apriori**
* **FP-Growth**

The generated rules are evaluated using:

* **Support**
* **Confidence**
* **Lift**

These rules are then used to recommend related products.

## 🔄 Workflow

```text
Transaction Data
      ↓
Data Cleaning
      ↓
Transaction Basket
      ↓
Transaction Encoding
      ↓
Apriori / FP-Growth
      ↓
Association Rules
      ↓
Support / Confidence / Lift
      ↓
Product Recommendations
      ↓
Cross-Selling
```

## 📊 Dataset

The project uses grocery transaction data containing information such as:

* Transaction ID
* Customer ID
* Product ID
* Product Name
* Quantity
* Unit Price
* Category
* Date

## 🧠 Association Rules

Example:

```text
WHITE BREAD → BUTTER
```

This indicates that **BUTTER** is associated with transactions containing **WHITE BREAD**.

### Metrics

| Metric     | Purpose                                      |
| ---------- | -------------------------------------------- |
| Support    | How frequently products occur together       |
| Confidence | How often B occurs when A occurs             |
| Lift       | Strength of the relationship between A and B |

**Lift > 1** generally indicates a positive association.

## 🛍️ Recommendation System

The system takes a product as input and recommends related products based on the generated association rules.

Example:

```text
Input:
WHITE BREAD

Recommendations:
1. BUTTER
2. CHIPS
3. COLD DRINK
```

Recommendations can be ranked using **Lift, Confidence, and Support**.

## 💰 Cross-Selling

The recommendations can be used for cross-selling.

```text
Customer buys WHITE BREAD
          ↓
Recommend BUTTER
          ↓
Additional Purchase
```

## 🛠️ Technologies

* Python
* Pandas
* NumPy
* MLxtend
* Jupyter Notebook

## 📁 Project Structure

```text
market-basket-analysis/
│
├── dataset/
│   └── blinkit_transaction_data.csv
│
├── Market_Basket_Analysis.ipynb
├── requirements.txt
└── README.md
```

## ⚙️ Installation

```bash
git clone https://github.com/parvvcodes/market-basket-analysis.git
cd market-basket-analysis

pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

## 🚀 Future Enhancements

* Streamlit web application
* Customer-specific recommendations
* Category-based recommendations
* Interactive visualizations
* REST API
* Real-time shopping-cart recommendations

## 👨‍💻 Author

**Parv Shah**

B.Tech — Computer Science & Technology

**Interests:** Python, Machine Learning, Data Science, Backend Development, Artificial Intelligence

---
