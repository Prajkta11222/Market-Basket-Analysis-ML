# 🛒 Market Basket Analysis using Machine Learning

## 📌 Project Overview

This project is about understanding how customers shop in a retail store. The idea is simple. When people shop, they usually buy multiple items together. By analyzing this data, we can find patterns and understand which products are often purchased together.

Using this information, we can also build a small recommendation system that suggests products based on what a customer is buying.

🔗 **GitHub Link:**
[https://github.com/Prajkta11222/Market-Basket-Analysis-ML](https://github.com/Prajkta11222/Market-Basket-Analysis-ML)

---

## 📂 Dataset

* Dataset used: **DMart Grocery Sales / Retail Dataset**
* It contains details of customer orders
* Each **Order ID = one transaction**
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

## 🔍 How the Project Works

First, the data is cleaned and organized.
Then, items are grouped based on Order ID so that each order becomes a basket of items.

After that:

* Data is converted into binary format (0 and 1)
* Patterns are found using different algorithms
* Rules are generated
* Finally, a recommendation system is created

---

## 🤖 Models Used

* **Apriori** → Finds common item combinations (but slow)
* **FP-Growth** → Faster version of Apriori (best performer)
* **Eclat** → Uses a different method (set-based)
* **Association Rules** → Shows relationships between items
* **K-Means** → Groups similar transactions
* **Recommendation System** → Suggests products

---

## 📊 Example Rule

**Soft Drinks → Health Drinks**

This means customers who buy soft drinks may also buy health drinks.

---

## 📊 Key Results

* Most purchased items:

  * Health Drinks
  * Soft Drinks
  * Cookies
  * Breads & Buns

* Found useful product relationships

* Built a working recommendation system

---

## 🛍️ Where This Can Be Used

* Retail stores → better product placement
* Online shopping → product suggestions
* Marketing → combo offers
* Inventory → stock planning

---

## ▶️ How to Run the Project

1. Open the notebook in Google Colab
2. Upload the dataset
3. Run all the cells
4. Check the output (graphs and rules)
5. Try recommendation function:

```python
recommend('Soft Drinks')
```

---

## ⚠️ Note

Train-test split is not used because this is an **unsupervised learning project**. We are finding patterns, not predicting values.

---

## 📁 Project Structure

```
Market-Basket-Analysis-ML/
│
├── Market_Basket_Analysis.ipynb
├── DMart_Grocery_Sales_-_Retail_Analytics_Dataset.csv
├── README.md
```

---

## 👥 Contributors

* Prajkta Padare (CS23031) 
* Vaishnavi Junghare (CS23024)

---

## 🚀 Conclusion

This project shows how we can use machine learning to understand customer behavior and make useful product recommendations. It is simple but very useful in real-world retail situations.

---

## ⭐ Future Scope

* Improve recommendation system
* Use bigger datasets
* Convert into a web application
