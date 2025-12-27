# 🛍️ Customer Segmentation using Machine Learning

A complete **end-to-end customer segmentation project** using **K-Means Clustering** to analyze customer behavior and identify meaningful groups for business decision-making.



## 🚀 Project Overview

Customer segmentation plays a key role in understanding consumer behavior and improving marketing strategies.  
In this project, we use **unsupervised machine learning** to group customers based on their purchasing patterns.

This project demonstrates:
- Data preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature selection  
- Clustering using K-Means  
- Data visualization  



## 📊 Dataset Information

- **Dataset Name:** Mall Customers Dataset  
- **Source:** Public dataset  
- **Features Used:**
  - Gender  
  - Age  
  - Annual Income (k$)  
  - Spending Score (1–100)  



## 🧠 Problem Statement

To segment customers into meaningful groups based on spending behavior and income, helping businesses:
- Target the right audience  
- Improve customer engagement  
- Optimize marketing strategies  



## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries Used:**
  - NumPy  
  - Pandas  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  



## 🔍 Project Workflow

### 1️⃣ Data Loading & Cleaning
- Loaded dataset using Pandas  
- Checked data types and null values  
- Removed unnecessary columns  

### 2️⃣ Exploratory Data Analysis (EDA)
- Distribution analysis of:
  - Age  
  - Annual Income  
  - Spending Score  
- Gender-based insights  

### 3️⃣ Feature Selection
Selected important features such as:
- Age vs Spending Score  
- Annual Income vs Spending Score  

### 4️⃣ Model Building (K-Means Clustering)
- Used **Elbow Method** to determine optimal clusters  
- Applied **K-Means algorithm**  
- Labeled customer segments  

### 5️⃣ Visualization
- Cluster visualization using scatter plots  
- Clear differentiation of customer groups  



## 📈 Results & Insights

- Customers were grouped into **distinct clusters** based on behavior  
- Identified:
  - High-income high-spending customers  
  - Budget-conscious customers  
  - Average spenders  
- These insights can help businesses improve:
  - Personalized marketing  
  - Customer retention  
  - Product recommendations  



## 🧪 How to Run This Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/ProblemShooter/customer-segmentation-ml.git
cd customer-segmentation-ml
