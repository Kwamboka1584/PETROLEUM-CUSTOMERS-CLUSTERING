# PETROLEUM-CUSTOMERS-CLUSTERING
# Sicah Energies Customer Segmentation Project

## Project overview
This project aims to identify distinct customer segments for Sicah Energies, a petroleum company seeking to understand customer purchasing behavior across fuel stations. Using **K-Means Clustering**, the project groups customers based on their fuel usage, spending habits, and loyalty characteristics. The insights generated support data-driven marketing strategies and customer engagement improvements.

## Business Objective
The primary business goals are to:
- Identify meaningful customer segments based on behavioral and spending patterns.
- Understand which customer groups contribute most to revenue.
- Recommend targeted marketing strategies to improve loyalty and retention.
- Optimize resource allocation and customer relationship management.

## Data Description
The dataset contains records of 500 customers, with attributes such as:
- `customer_id` — Unique customer identifier  
- `station_id` — Fuel station associated with the customer  
- `avg_monthly_litres` — Average litres of fuel purchased per month  
- `avg_monthly_spend` — Average monthly spending  
- `visits_per_month` — Frequency of station visits per month  
- `loyalty_score` — Numeric measure of customer loyalty  
- `preferred_fuel`, `payment_method`, `location_type` — Categorical attributes representing customer preferences

## Tools and Technologies
- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Visualization:** Matplotlib & Seaborn  
- **Modeling:** K-Means Clustering  

## Project Workflow
The project follows a structured Data Science pipeline:
1. **Business Understanding** – Define the business need and goals.  
2. **Data Understanding** – Load, inspect, and summarize the dataset.  
3. **Exploratory Data Analysis (EDA)** – Identify trends and correlations among customer features.  
4. **Data Preparation** – Handle missing values, encode categorical variables, and scale numerical features.
5. **Modeling (K-Means Clustering)** –  
   - Determine optimal clusters using Elbow & Silhouette methods.  
   - Assign customers to clusters.  
6. **Cluster Profiling & Interpretation** – Describe the key traits of each cluster.  
7. **Insights & Recommendations** – Translate findings into actionable business strategies.  

## Visualizations
Below are some of the visualizations from the project.
