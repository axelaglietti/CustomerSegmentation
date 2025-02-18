# Customer Segmentation and Marketing Insights

This project analyzes customer purchasing behavior for a hypothetical e-commerce business, "ShopSphere," using a publicly available dataset to simulate real-world challenges faced by online retailers. The goal is to develop data-driven insights that inform personalized marketing strategies and business decisions.

## 📌 Project Overview

- **Objective:**  
  The project aims to segment customers based on their purchasing behavior, identifying distinct customer personas. These insights enable businesses to optimize their marketing strategies and enhance customer engagement.

- **Techniques Used:**  
  - Data preprocessing (handling missing values, outliers, and feature engineering).  
  - Exploratory Data Analysis (EDA) to identify key trends and patterns.  
  - Machine Learning (Clustering algorithms, such as K-Means) to categorize customers into meaningful segments.  

## 📊 Dataset

- **Source:** [Online Retail Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset)
- **Description:** This dataset contains transactional data for a UK-based online retail company between 01/12/2010 and 09/12/2011, detailing customer purchases, product categories, and sales amounts.
- **License:** Attribution 4.0 International (CC BY 4.0)

## 📂 Repository Structure

- `analysis.ipynb` → Jupyter Notebook containing the data analysis and clustering process.
- `online_retail.xlsx` → The dataset used for analysis (if sharing is allowed).
- `requirements.txt` → List of Python libraries required to run the notebook.

## 🚀 Methodology

1. **Data Preprocessing:**  
   - Handled missing values and removed duplicates.  
   - Filtered transactions with positive quantities and unit prices.  
   - Created a new `TotalPrice` feature for revenue analysis.

2. **Exploratory Data Analysis (EDA):**  
   - Analyzed geographical distribution of sales.  
   - Examined sales trends over time to identify peak seasons.  
   - Investigated product categories with the highest demand.  

3. **Customer Segmentation:**  
   - Applied **K-Means clustering** to group customers based on their **spending patterns and purchase frequency**.  
   - Developed **customer personas**, considering factors like total revenue contribution and purchase habits.  
   - Identified **high-value customers**, **frequent buyers**, and **occasional shoppers** to tailor business strategies.  

## 📈 Results & Insights

- The dataset was split into two subsets:  
  - One including **CustomerID** to analyze **individual purchasing behavior**.  
  - One excluding **CustomerID** to detect **overall sales patterns** without bias.  

- **Key Findings:**  
  - The **United Kingdom** had the highest number of transactions, significantly influencing sales trends.  
  - Clustering analysis revealed **three main customer segments**:
    1. **High-Spending Regulars** – Customers who frequently purchase and generate high revenue.  
    2. **Occasional Buyers** – Customers who shop sporadically with moderate spending.  
    3. **Bargain Shoppers** – Customers making low-cost purchases or engaging in bulk buying.  

- These insights allow for **personalized marketing campaigns**, such as **loyalty programs for high-value customers** and **targeted promotions for occasional buyers**.
