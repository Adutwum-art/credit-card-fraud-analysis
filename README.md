Credit Card Fraud Analysis

Exploratory Data Analysis (EDA) to identify patterns and anomalies in credit card transactions that may indicate fraudulent activity.



## 📌 Project Overview
This project analyzes credit card transaction data to detect unusual behavioral patterns that may signal potential fraud.

The objective is to simulate a real-world banking scenario where a Data Analyst identifies risks using historical transaction data and recommends early detection strategies.

---

## 🧠 Problem Statement

Credit card fraud often occurs without physical card theft, using compromised credentials for online purchases.

Early detection depends on identifying abnormal patterns in user behavior such as transaction spikes, location inconsistencies, and unusual spending habits.

---

## 📁 Data Understanding

The dataset includes the following key attributes:

- Customer details  
- Transaction amounts  
- Transaction frequency  
- Location and IP-related information  
- Delivery preferences  

---

## 🧹 Data Preparation

- Handled missing and inconsistent values  
- Standardized date formats  
- Ensured data quality and consistency for analysis  

---

## 📈 Exploratory Data Analysis (EDA)

The following fraud indicators were analyzed:

### 1. Transaction Frequency
- Identified users with unusually high transaction activity  
- Detected rapid transactions within short time intervals  

### 2. High-Value Transactions
- Compared transaction amounts against user averages  
- Flagged abnormal spending spikes  

### 3. Bulk Purchase Behavior
- Detected repeated purchases of similar items with variations  
- Identified unusual ordering patterns  

### 4. Location & IP Mismatch
- Identified inconsistencies between billing location and IP address  

### 5. Delivery Behavior Changes
- Detected sudden changes in delivery preferences (e.g., home → PO box or pickup points)  

---

## 🚨 Key Insights

- Sudden spikes in transaction frequency may indicate compromised accounts  
- High-value transactions outside normal user behavior are strong fraud indicators  
- Location and IP mismatches increase fraud risk probability  
- Changes in delivery behavior may signal account misuse  

---

📊 Visualizations
The analysis includes visual exploration of transaction behavior to identify anomalies.

## Transaction Value Distribution

![Transaction Value Chart](transaction_value_chart.png)

This visualization highlights:
- Normal spending ranges
- High-value outliers
- Potential fraudulent spikes in transaction amounts
---

🛠 Tools & Techniques Used

- Microsoft Excel  
- Data Cleaning Techniques  
- Exploratory Data Analysis (EDA)  
- Pattern Recognition  
- Data Visualization  



 📌 Recommendations

- Implement real-time transaction monitoring systems  
- Flag high-frequency and high-value transactions  
- Use geolocation verification for fraud detection  
- Monitor sudden behavioral changes in user activity  



📊 Skills Demonstrated

- Data Cleaning  
- Exploratory Data Analysis (EDA)  
- Anomaly Detection Thinking  
- Fraud Pattern Recognition  
- Data Interpretation  
