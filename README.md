# Market Basket Analysis & Cross-Selling Recommendation System

A data-driven recommendation system that uses **Market Basket Analysis** and **Association Rule Mining** to identify relationships between products and generate **cross-selling recommendations** from grocery transaction data.

---

## Overview

This project analyzes grocery transaction data to discover **customer purchasing patterns** and identify products that are frequently purchased together.

The system implements two popular frequent-itemset mining algorithms:

- **Apriori**
- **FP-Growth**

After identifying frequent itemsets, the project generates **association rules** using:

- **Support**
- **Confidence**
- **Lift**

These rules are then used to build a **product recommendation system**. The recommendations can be applied as a **cross-selling strategy** by suggesting complementary products that customers are likely to purchase along with their selected product.

### Example

If the analysis identifies the relationship:

```text
WHITE BREAD → BUTTER
