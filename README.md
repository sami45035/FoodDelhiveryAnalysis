# FoodDelhiveryAnalysis
Exploratory Data Analysis on a food delivery dataset using Python, focusing on user behavior, city-wise performance, 

# 🍔 Food Delivery Data Analysis (EDA Project)

## 📌 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a food delivery dataset created by integrating data from multiple sources. The goal is to uncover meaningful insights related to user behavior, restaurant performance, revenue trends, and membership impact.

This project was completed as part of an **internship qualification / assessment task**.

---

## 📂 Dataset Description
The final dataset was created by merging:
- **Orders data** (CSV)
- **Users data** (JSON)
- **Restaurants data** (SQL)

Each row in the dataset represents a single food order.

### Key Columns:
- `order_id` – Unique order identifier  
- `user_id` – User identifier  
- `restaurant_id` – Restaurant identifier  
- `order_date` – Date of order  
- `total_amount` – Order value  
- `name` – User name  
- `city` – User city  
- `membership` – Membership type (Gold / Regular)  
- `restaurant_name` – Restaurant name  
- `cuisine` – Cuisine type  
- `rating` – Restaurant rating  

---

## 🧹 Data Cleaning & Preparation
- Data loaded from CSV, JSON, and SQL formats  
- Datasets merged using **left joins** to retain all orders  
- Data types and structure validated  
- Date column converted to datetime format  
- Duplicate and redundant columns handled  
- No critical missing values found in key identifiers  

---

## 📊 Exploratory Data Analysis
The EDA was performed using:
- **Univariate analysis** (distribution and counts)
- **Bivariate analysis** (relationships between variables)
- **Multivariate analysis** (pivot tables)
- **Time-based analysis** (monthly trends)

### Key Analyses:
- Order amount distribution  
- Membership-wise order behavior  
- City-wise and cuisine-wise performance  
- Revenue trends over time  
- Pivot table analysis across city, cuisine, and membership  

---

## 🔍 Key Observations
- Membership distribution is nearly balanced between Gold and Regular users  
- Gold members show higher average order values  
- Revenue contribution varies significantly across cities  
- Certain cuisines are consistently more popular  
- Higher-rated restaurants tend to generate more revenue  
- Clear seasonal patterns observed in order volume and revenue  

---

## 🧾 Conclusion
The analysis highlights important trends in customer behavior and restaurant performance. Membership type, city, and cuisine play a crucial role in influencing revenue. The final dataset serves as a reliable source for data-driven insights and business decision-making.

---

## 🛠️ Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📁 Project Structure
```

├── data/
│   ├── orders.csv
│   ├── users.json
│   ├── restaurants.sql
├── notebook/
│   └── EDA_Internship_Project.ipynb
├── final_food_delivery_dataset.csv
└── README.md
