# Task-1-of-internship
#  Customer Behavior Analytics & Churn Prediction Dashboard

##  Project Overview
This project was developed as part of the **TEYZIX CORE Internship Program (Task 1 / ID: DA-INT-1)**. 
The objective is to build an end-to-end data analytics and machine learning system that transforms raw customer data into actionable business insights. It predicts the probability of customer churn and classifies them into risk tiers, helping retention teams take proactive measures.

##  Dataset Details
* **Source:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`
* **Size:** 7,043 rows and 21 columns
* **Target Feature:** `Churn` (Yes / No)

##  Project Modules Covered
1. **Data Analysis & Cleaning:** Handled data type conversions (e.g., converting `TotalCharges` to numeric) and resolved hidden missing values.
2. **Feature Engineering:** Grouped customer tenure into distinct operational brackets and created behavior-based spending segments.
3. **Exploratory Data Visualization:** Created distributions, revenue trends, and correlation heatmaps utilizing `matplotlib` and `seaborn`.
4. **Machine Learning Pipeline:** Preprocessed categorical values via Label Encoding and trained **Logistic Regression** and **Random Forest** models.
5. **Customer Risk Classification System:** Generated exact churn probability metrics and tiered users into **Low, Medium, and High Risk** pools.

## Key Business Insights Discovered
* **Contract Risks:** Customers on a **Month-to-month** contract showcase an aggressively higher churn velocity compared to stable 1-year or 2-year subscribers.
* **Financial Danger Zone:** High monthly billings between **$70 and $100+** create a prominent friction area where customer retention levels fall sharply.
* **Predictive Value:** The machine learning architecture achieves an overall accuracy of **~80%**, empowering corporate retention cells to catch 4 out of 5 churners ahead of time.

## Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## ⚙️ How to Run the Project
1. Clone this repository to your desktop.
2. Ensure you have Jupyter Notebook or Anaconda installed.
3. Open `DA_INT_1_Customer_Churn_Dashboard.ipynb` and run the cells sequentially.
