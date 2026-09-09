@"
# 🛒 Market Basket Analysis & Product Recommendation System

## 📌 Overview

This project performs **Market Basket Analysis** on a Blinkit grocery transaction dataset to identify customer purchasing patterns and discover products that are frequently purchased together.

The project uses **Apriori** and **FP-Growth** algorithms to generate frequent itemsets and association rules. These rules are then used to build a simple **Product Recommendation System** that recommends products based on a selected product.

## 🎯 Objectives

- Analyze customer purchasing patterns.
- Identify frequently purchased products.
- Generate frequent itemsets using **Apriori** and **FP-Growth**.
- Generate association rules using **Support, Confidence, and Lift**.
- Build a product recommendation system.
- Generate recommendations using both algorithms.
- Combine recommendations and remove duplicate products.

## 📊 Dataset

The project uses the **Blinkit grocery transaction dataset**.

### Dataset Features

| Column | Description |
|---|---|
| `Transaction_ID` | Unique transaction identifier |
| `Customer_ID` | Unique customer identifier |
| `Date` | Transaction date |
| `Product_ID` | Product identifier |
| `Product_Name` | Name of the purchased product |
| `Quantity` | Quantity purchased |
| `Unit_Price` | Price per unit |
| `Category` | Product category |

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Create Transaction Basket
   ↓
Transaction Encoding
   ↓
Apriori Algorithm
   ↓
Apriori Association Rules
   ↓
FP-Growth Algorithm
   ↓
FP-Growth Association Rules
   ↓
Product Recommendation
   ↓
Final Recommendations