# 📊 Market Basket Analysis & Association Rule Mining

Understanding patterns in transactional data for **data-driven decision making**

---

## 📌 Overview

This repository contains a presentation on **Market Basket Analysis (MBA)** and **Association Rule Mining**, focusing on how businesses can uncover hidden relationships in transactional data to improve **product placement, promotions, and cross-selling strategies**.

The presentation explains both **theoretical concepts** and **real-world business applications** in a clear, structured, and practical manner.

---

## 🎯 Objectives

- Understand what Market Basket Analysis is and why it matters  
- Learn how association rules help discover item relationships  
- Explore popular algorithms like **Apriori** and **FP-Growth**  
- Understand different extensions of association rule mining  
- See how these techniques create real business value  

---

## 🛒 What is Market Basket Analysis?

Market Basket Analysis is a data mining technique used to identify patterns and relationships among items in transactional datasets.

It answers questions such as:
- Which products are frequently purchased together?
- How can stores improve product placement?
- Which items should be bundled or promoted together?

### 🔍 Real-World Example
> Customers who buy **bread** are highly likely to also buy **butter**

### 💼 Business Impact
- Strategic product placement  
- Effective bundle offers  
- Increased basket size  
- Improved cross-selling opportunities  

---

## 📈 Association Rule Metrics

Association rules are evaluated using key metrics:

- **Support** – Frequency of an itemset in the dataset  
- **Confidence** – Reliability of the rule  
- **Lift** – Strength of association beyond random chance  

These metrics help businesses make **data-driven decisions** instead of assumptions.

---

## ⚙️ Apriori Algorithm

Apriori is a classic algorithm used to mine frequent itemsets.

### Key Steps:
1. **Candidate Generation** – Generate k-itemsets from (k-1)-itemsets  
2. **Support Counting** – Measure frequency of each candidate  
3. **Pruning** – Remove infrequent itemsets  
4. **Rule Generation** – Create association rules  

✔ Simple and interpretable  
❌ Computationally expensive for large datasets  

---

## 🚀 FP-Growth Algorithm

FP-Growth is an optimized alternative to Apriori.

### Why FP-Growth?
- Eliminates candidate generation  
- Uses a compressed **FP-Tree** structure  
- Requires fewer database scans  
- Highly efficient for large transaction datasets  

### Key Advantages:
- Faster execution  
- Reduced memory usage  
- Scales well for massive databases  

---

## 🧱 Vertical Data Format Approach

Instead of storing transactions horizontally, data is stored vertically.

### How it Works:
1. **Vertical Representation**  
   Each item maps to a list of transaction IDs (TIDs)

2. **Intersection Operations**  
   Frequent itemsets are found by intersecting TID lists

3. **Efficiency Gains**  
   - Fewer database scans  
   - Improved computational performance  

---

## 🔒 Closed Frequent Itemsets

Closed frequent itemsets reduce redundancy while preserving information.

### Definition:
A frequent itemset is **closed** if no superset has the same support.

### Benefits:
- Concise pattern representation  
- Removes unnecessary supersets  
- Maintains complete support information  
- Improves interpretability  

---

## 🏗 Multilevel Association Rules

These rules discover patterns at **different levels of abstraction** using concept hierarchies.

### Levels:
- **Category Level** – Electronics  
- **Subcategory Level** – Laptops  
- **Product Level** – Gaming Laptops  

This enables flexible insights depending on business needs.

---

## 🧩 Multidimensional & Correlation Analysis

### Multidimensional Rules
Rules involving attributes beyond purchased items.

**Example:**
{Age: 20–30, Gender: Male} → Buys: Video Games


### Correlation Metrics
- Lift  
- Conviction  
- Pearson Correlation  

These metrics identify **true relationships**, not just coincidental co-occurrence.

---

## 🎯 Constraint-Based Mining

Constraint-based mining focuses on **actionable and relevant patterns**.

### Why Use Constraints?
- Reduces search space  
- Improves efficiency  
- Filters irrelevant patterns early  
- Increases business value  

### Types of Constraints:
- **Item Constraints** – Specific items or categories  
- **Aggregate Constraints** – Minimum/maximum support  
- **Rule Length Constraints** – Limit number of items in rules  

---

## 💡 Key Takeaways

- Market Basket Analysis helps uncover hidden purchasing patterns  
- Association rules enable smarter business decisions  
- FP-Growth is more scalable than Apriori  
- Advanced techniques improve efficiency and interpretability  
- These methods are widely used in retail, e-commerce, and marketing analytics  

---

## 📂 Repository Contents

- `Market-Basket-Analysis-and-Association-Rule-Mining-final.pptx`  
  → Presentation explaining all concepts in detail  

---

## 👩‍💻 Author

**Divya Tripathi**  
RA2311003030547  
B.Tech CSE Core – III Year / VI Semester  

---

## 📜 License

This project is for **academic and educational purposes**.

---

⭐ *If you find this useful, feel free to star the repository!*
## 👩‍💻 Author

**Created by:** 
Divya Tripathi (**divyat2605**)  
  
