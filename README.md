# 🍔 Food Delivery Data Analysis (Hackathon Project)

## 📌 Project Overview
This project combines transactional, user, and restaurant datasets from different formats (CSV, JSON, SQL) to create a unified analytics dataset.

## 📂 Datasets Used
- orders.csv – Order-level transactional data
- users.json – User master data
- restaurants.sql – Restaurant master data

## 🔧 Tools & Technologies
- Python
- Pandas
- SQLite
- Jupyter Notebook
- Anaconda

## 🔗 Data Integration
- orders.csv ↔ users.json using user_id (LEFT JOIN)
- orders.csv ↔ restaurants.sql using restaurant_id (LEFT JOIN)

## 📊 Key Insights
- Revenue analysis by city and cuisine
- Gold vs Regular membership behavior
- Restaurant performance analysis
- Seasonal revenue trends

## 📁 Output
- final_food_delivery_dataset.csv (Single source of truth)

## 👨‍💻 Author
Varun Bhalerao
