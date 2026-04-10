# 🛒 Market Basket Analysis using Machine Learning

## 📌 Project Overview

This project performs **Market Basket Analysis** on a retail dataset to discover relationships between products frequently purchased together. The goal is to extract meaningful patterns and build a recommendation system based on customer purchase behavior.

Github Link : https://github.com/Prajkta11222/Market-Basket-Analysis-ML
---

## 📂 Dataset

* **Name:** DMart Grocery Sales / Retail Dataset
* Contains transaction-level data such as Order ID, Category, Sub Category, etc.
* Each order is treated as a transaction
* Items are taken from the **Sub Category column**

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
2. Transaction Formation using Order ID  
3. Creation of multi-item baskets  
4. One-Hot Encoding using TransactionEncoder  
5. Exploratory Data Analysis (Top purchased items)  
6. Model Implementation  
7. Pattern Discovery and Rule Generation  
8. Recommendation System  

---

## 🤖 Machine Learning Models Implemented

### 1. Apriori Algorithm
* Generates frequent itemsets  
* Identifies commonly purchased combinations  

### 2. FP-Growth Algorithm
* Faster than Apriori  
* Efficient for larger datasets  

### 3. Eclat Algorithm
* Uses vertical data format  
* Finds itemsets using intersection  

### 4. Association Rule Mining
* Generates rules using:
  * Support  
  * Confidence  
  * Lift  

### 5. K-Means Clustering
* Groups transactions into clusters  
* Identifies similar buying patterns  

### 6. Recommendation System
* Suggests items based on association rules  

---

## 📊 Example of Association Rule

Example rule generated from the dataset:

**{Soft Drinks} → {Health Drinks}**

* Confidence: ~0.15  
* Lift: ~0.76  

👉 Interpretation:  
Customers who buy *Soft Drinks* are also likely to buy *Health Drinks*.

---

## 🛍️ Real-World Applications

* **Retail Stores:**  
  Better product placement  

* **E-commerce:**  
  Recommendation systems  

* **Supermarkets:**  
  Cross-selling strategies  

* **Marketing:**  
  Combo offers  

* **Inventory Management:**  
  Stock planning  

---

## 📊 Key Results

* Top purchased items:
  * Health Drinks  
  * Soft Drinks  
  * Cookies  
  * Breads & Buns  

* Discovered relationships between product categories  
* Built a working recommendation system  

---

## ⚠️ Note

Train-test split is not applied because this is an **unsupervised learning problem**.  
There is no target variable, and the goal is to find patterns in the data.

---

## 📁 Project Structure
Market-Basket-Analysis-ML/
│
├── Market_Basket_Analysis.ipynb
├── DMart_Grocery_Sales_-_Retail_Analytics_Dataset.csv
├── README.md

---

## 👥 Contributors

* Prajkta Padare (CS23031)  
* Vaishnavi Junghare (CS23024)  

---

## 🚀 Conclusion

This project shows how unsupervised learning techniques can be used to analyze purchasing behavior and generate useful product recommendations for retail businesses.

---

## ⭐ Future Scope

* Improve recommendation system  
* Use real large-scale datasets  
* Deploy as a web application  
