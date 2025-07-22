# 📉 Customer Churn Dashboard – Power BI

## 🎯 Objective

To analyze churn patterns in a telecom company’s customer base and help identify key risk segments using interactive visualizations, so the business can proactively reduce churn and boost retention.

---

## 📁 Dataset Overview

- **Source**: IBM Sample Telco Customer Churn Dataset  
- **Records**: 6,418 customers  
- **Fields**: Demographics, Services Used, Account Info, Tenure, Monthly Charges, Contract Type, Payment Method, Churn Flag, etc.

---

## 📊 Key Metrics

- **Total Customers**: 6,418  
- **New Joiners**: 411  
- **Churned Customers**: 1732  
- **Churn Rate**: 27.0%

---

## 📌 Business Questions Answered

- What is the churn rate across various age groups, states, and contract types?
- Which services or customer segments are more likely to churn?
- How do payment method and contract duration impact churn?
- What reasons are driving customer churn?

---

## 📈 Dashboard Features

### 🔹 Main Dashboard
- **KPIs**: Total Customers, New Joiners, Total Churn, Churn Rate
- **Churn Analysis** by:
  - Gender
  - Age Group
  - Payment Method
  - Contract Type
  - Geography (State-wise Churn) (with button to watch more states details)
  - Tenure Segment
  - Churn Category (with drill-down)
  - Services

### 🔸 Drill-Down (via Graph)
- Detailed churn reasons with Total and percent distribution:
  - Price, Product/Service dissatisfaction
  - Network reliability
  - Poor customer support

### 🔸 Button-Linked Screen
- **State-wise Map View** with churn count and rate
- Visual drill-down of regional churn trends across India

---

## 💡 Final Insights

- **Gender**: Female customers have higher churn (64%)
- **Age**: Seniors (Above 80 yrs) have the highest churn rate (44.6%)
- **Top States by Churn Rate**: 
  - Jammu & Kashmir (57.2%)
  - Assam (38.1%)
  - Jharkhand (34.5%)
- **Contract Type**:
  - Month-to-Month users churn the most (46.5%)
  - 2-Year contracts reduce churn drastically (2.7%)
- **Internet & Services**:
  - Fiber Optic users: 41.1% churn
  - Internet Service (93.71%), Phone Service (90.59%), Unlimited Data (80.08%) linked to high churn
- **Churn Drivers**:
  - Price, Customer Support, and Product Dissatisfaction are top reasons

---

## 🛠 Tools Used

- **Power BI** for dashboard creation  
- **Power Query** for data preparation  
- **DAX** for KPIs and logic-based measures

---

## 📂 File Contents

- `Customer_Churn_Dashboard.pbix` – Full Power BI file  
- `README.md` – Project overview and insights  
- `churn_dashboard_preview.png` – Static preview image  

---

## ✅ Outcome

This dashboard empowers decision-makers to:
- Identify high-risk customers by geography, services, and tenure  
- Understand churn causes and behaviors  
- Design more effective customer retention and loyalty strategies
