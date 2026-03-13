
CS23024,CS23031

# 🛒 Market Basket Analysis using Machine Learning

## 📌 Project Overview

Market Basket Analysis is a data mining technique used to discover relationships between items that customers frequently purchase together.

In this project, we analyze grocery store transaction data to identify **frequent itemsets and association rules**. These patterns help retailers understand customer buying behavior and can be used for **product recommendations, store layout optimization, and targeted marketing strategies**.

The project is implemented using **Python in Google Colab** and maintained on **GitHub with daily commits** to track development progress.

---

## 🎯 Project Objectives

* Analyze grocery store transaction data
* Identify products frequently bought together
* Implement multiple machine learning algorithms for pattern discovery
* Generate association rules using support, confidence, and lift
* Build a simple recommendation system based on discovered patterns

---

## 📊 Dataset

**Dataset Name:** Groceries Dataset

The dataset contains a collection of grocery transactions where each transaction includes a list of items purchased together.

Example transaction:

Milk, Bread, Butter
Beer, Chips
Milk, Bread

Each transaction is analyzed to identify patterns of frequently co-occurring items.

---

## 🤖 Machine Learning Models Implemented

This project implements the following six models:

1. Apriori Algorithm
2. FP-Growth Algorithm
3. Eclat Algorithm
4. Association Rule Mining
5. K-Means Clustering for customer purchase patterns
6. Product Recommendation System

---

## ⚙️ Technologies Used

* Python
* Google Colab
* Pandas
* MLxtend
* Matplotlib
* GitHub

---

## 🔄 Project Workflow

1. Load the Groceries dataset
2. Perform data preprocessing and cleaning
3. Convert transactions into encoded format
4. Apply machine learning algorithms
5. Generate frequent itemsets
6. Create association rules
7. Visualize results and analyze patterns
8. Build recommendation logic

---

## 📂 Repository Structure

```
Market-Basket-Analysis-ML
│
├── Market_Basket_Analysis.ipynb
├── groceries.csv
├── README.md
```

---

## 📈 Example Association Rule

Milk → Bread

Support: 0.04
Confidence: 0.65
Lift: 1.8

This rule indicates that customers who purchase **milk** are likely to purchase **bread** as well.

---

## 🛍 Applications

Market Basket Analysis is widely used in:

* Supermarkets
* Retail analytics
* E-commerce recommendation systems
* Inventory management
* Marketing strategy optimization

---

## 👥 Team Members

* **Member 1:** Prajkta Padare(CS23031)
* **Member 2:** Vaishanavi Junghare(CS23024)

---

## 🚀 Future Improvements

* Use larger retail datasets
* Implement deep learning based recommendation systems
* Build a web-based interface for product recommendations

---

## 📌 Conclusion

Market Basket Analysis provides valuable insights into customer purchasing behavior. By discovering relationships between products, retailers can enhance product placement, improve recommendations, and increase overall sales.
