# 🛒 Customer Retention & Churn Prediction Project (Power BI + Python)

A complete business analytics and machine learning project to analyze and predict customer churn in an e-commerce scenario. Built using Power BI for dashboarding and Python (Logistic Regression) for churn modeling.

---

## 📌 Project Overview

This project combines exploratory analytics and predictive modeling to solve a common business problem: improving customer retention in a marketplace-like environment (inspired by platforms such as Meesho, Flipkart, etc.).

✅ Dashboard to monitor user behavior & retention  
✅ ML model to predict churn likelihood  
✅ Data storytelling with insights for actionable business decisions

---

## 🧩 Tools & Technologies

- Power BI (dashboard, DAX, slicers, KPIs)
- Python (Pandas, Scikit-learn, NumPy)
- Logistic Regression (with class_weight handling)
- Google Colab (Jupyter environment)

---

## 📊 Power BI Dashboard Highlights

- 30 / 90-day Retention Rate and Churn Rate
- Repeat Purchase Rate (New → Repeat → Loyal Funnel)
- Segment-wise churn analysis by:
  - Region
  - Payment Method
  - Gender
  - Product Category
- Interactive slicers to deep-dive into behavior cohorts
- Insight cards with business recommendations

📷 (Add screenshots of your dashboard here)

---

## 🤖 Churn Prediction Model (Python)

Used behavior signals to build a binary classification model predicting whether a user is likely to churn.

### 🎯 Target Variable:
Users not active for more than 365 days were labeled as churned (`Churn = 1`)

### 🧾 Features used:
- Number of Orders
- Average Order Value
- Product Category Diversity
- Preferred Payment Method (Online/COD)
- Region & Gender

### 📈 Model:
- Logistic Regression (`class_weight='balanced'`)

### 📊 Performance:
- F1 Score (Churn class): 0.741
- Accuracy: 59.0%
- Top churn signals:
  - Low order count
  - COD preference
  - Limited category variety

✅ Coefficients converted to odds ratios for interpretability

---

## 📌 Business Recommendations

- Promote online payments → Associated with 40% lower churn odds
- Target low-frequency users early → Order count inversely related to churn
- Encourage category exploration → More diverse buyers churn less
- Region-based strategies → Higher churn observed in Southern regions

---

## 📁 Dataset

- Simulated dataset with 10,000+ orders and 1,000 users  
- Columns include: `User_ID`, `Order_ID`, `Order_Value`, `Product_Category`, `Payment_Type`, `Region`, `Gender`, `Signup_Date`, `Order_Date`

---

## ✅ What I Learned

- Real-world churn labeling using cohort logic
- Data visualization and storytelling with Power BI
- Building and interpreting classification models
- Handling class imbalance in ML
- Explaining model decisions with odds ratios

---

## 🚀 How to Use

1. Clone the repo and open the notebook (Colab / Jupyter)
2. Upload the dataset: `customer_retention_data.csv`
3. Run through churn labeling, feature engineering, and modeling
4. Explore churn probability outputs
5. Open Power BI `.pbix` file to explore insights visually

---

## ✍️ Author

Sakshi Joshi  


---

