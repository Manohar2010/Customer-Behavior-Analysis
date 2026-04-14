# Customer Behavior & Segmentation Analysis

## 📌 Project Overview
This project analyzes customer transaction data to understand spending behavior, purchase frequency, and customer value. The goal is to identify high-value customers and derive insights that can help improve business decisions.

---

## 📊 Dataset Description
The dataset contains:
- Customer IDs and order IDs  
- Order values  
- Order dates  
- Customer regions  

---

## 🧹 Data Cleaning
- Converted `order_date` to datetime format  
- Handled missing values:
  - Region → filled with "Unknown"  

---

## ⚙️ Feature Engineering

### Customer-Level Metrics
- `total_spent`: Total amount spent by each customer  
- `total_orders`: Number of orders per customer  
- `avg_order_value`: Average order value per customer  

### Recency
- Calculated the time difference between the latest order date and each customer’s last purchase  

### Customer Segmentation
Customers were segmented based on total spending:
- High Value (≥ 2000)  
- Medium Value (≥ 1000)  
- Low Value (< 1000)  

---

## 📈 Key Insights

### Top Customers
- A small group of customers contributes significantly to total revenue  
- Identifying these customers can help in targeted marketing  

### Regional Analysis
- Certain regions have higher average order values  
- Some regions generate more total revenue, indicating stronger market performance  

### Customer Segmentation
- High-value customers have significantly higher average spending  
- Majority of customers fall into medium and low-value segments  

### Customer Activity (Recency)
- Recently active customers can be targeted for retention strategies  
- Less active customers may require re-engagement campaigns  

---

## 🛠 Tools Used
- Python  
- Pandas  
- NumPy  

---

## 🚀 Future Improvements
- Add visualizations for better insights  
- Implement RFM (Recency, Frequency, Monetary) analysis  
- Build predictive models for customer lifetime value  
