# 🛒 Market Basket Analysis using Machine Learning

## 📌 Project Overview

This project performs **Market Basket Analysis** on a grocery dataset to discover relationships between products frequently purchased together. The goal is to extract meaningful patterns and build a recommendation system based on customer purchase behavior.

---

## 📂 Dataset

* **Name:** Groceries Dataset
* Contains transactional data of items purchased by customers
* Each transaction represents a list of items bought together

---

## ⚙️ Technologies Used

* Python
* Google Colab
* Pandas, NumPy
* Matplotlib
* Scikit-learn
* Mlxtend

---

## 🔍 Project Workflow

1. Data Loading and Cleaning
2. Transaction Formation (grouping items per customer)
3. One-Hot Encoding using TransactionEncoder
4. Exploratory Data Analysis (Top purchased items)
5. Model Implementation
6. Pattern Discovery and Rule Generation
7. Recommendation System

---

## 🤖 Machine Learning Models Implemented

### 1. Apriori Algorithm

* Generates frequent itemsets
* Identifies commonly purchased combinations

### 2. FP-Growth Algorithm

* Faster alternative to Apriori
* Efficient for large datasets

### 3. Eclat Algorithm

* Uses vertical data format
* Finds frequent itemsets using intersection

### 4. Association Rule Mining

* Generates rules using:

  * Support
  * Confidence
  * Lift

### 5. K-Means Clustering

* Groups customers based on purchase patterns
* Helps identify different buying behaviors

### 6. Recommendation System

* Suggests items based on association rules

---

## 📊 Example of Association Rule

Example rule generated from the dataset:

**{yogurt} → {whole milk}**

* Confidence: 0.12
* Lift: 0.82

👉 Interpretation:
Customers who buy *yogurt* are likely to also buy *whole milk*.

---

## 🛍️ Real-World Applications

* **Retail Stores:**
  Arrange products together (e.g., milk near bread)

* **E-commerce (Amazon, Flipkart):**
  “Customers who bought this also bought” recommendations

* **Supermarkets:**
  Product placement optimization

* **Marketing Strategies:**
  Bundle offers (e.g., buy chips + get soda discount)

* **Inventory Management:**
  Stock frequently purchased item combinations

---

## 📊 Key Results

* Identified frequently purchased items:

  * Whole milk
  * Other vegetables
  * Rolls/buns
* Discovered relationships between products
* Built a recommendation system based on customer behavior

---

## ⚠️ Note

Train-test split is not applied in this project because **Market Basket Analysis is an unsupervised learning technique**. It does not involve a target variable or prediction task, so the entire dataset is used for pattern discovery.

---

## 📁 Project Structure

```
Market-Basket-Analysis-ML/
│
├── Market_Basket_Analysis.ipynb
├── Groceries_dataset.csv
├── README.md
```

---

## 👥 Contributors

* Prajkta Padare(CS23031)
* Vaishnavi Junghare (CS23024)

---

## 🚀 Conclusion

This project demonstrates how unsupervised machine learning techniques can be used to analyze customer purchasing behavior and generate useful product recommendations for retail businesses.

---

## ⭐ Future Scope

* Improve recommendation system using collaborative filtering
* Deploy as a web application
* Use larger real-world datasets

---
