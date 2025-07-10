# Data-Driven Demand Forecasting and Stock Optimization for an Army CSD

This repository presents a comprehensive data analytics project focused on **demand forecasting** and **inventory optimization** for the **Army Canteen Stores Department (CSD)**, specifically the **MP Sub Area Unit Run Canteen located in Bhopal Cantt, Madhya Pradesh, India**.

The objective of this project is to **minimize stockouts and overstocking** by applying statistical methods, forecasting models, and optimization algorithms to streamline procurement and inventory practices.


---

## 🔍 Problem Statement

The Army CSD faces challenges in maintaining optimal inventory levels due to:
- Fluctuating item-level demand
- Static procurement cycles
- Uniform reorder policies across diverse categories
- High frequency of overstock (2,781 events) and occasional stockouts (111 events)

These inefficiencies lead to blocked capital, increased holding costs, and suboptimal service availability.

---

## 🛠️ Tools & Technologies Used

- **Python (Pandas, NumPy, Matplotlib, Seaborn, Statsmodels)**
- **Google Colab**
- **ARIMA Forecasting**
- **EOQ Optimization**
- **ABC Analysis**
- **Descriptive Statistics**
- **Data Visualization**

---

## 📊 Key Analyses Performed

- **Descriptive Statistics** to understand distribution of stock, demand, and price
- **EOQ Calculation** to recommend ideal reorder quantities
- **Stockout/Overstock Risk Flagging** based on dynamic thresholds
- **Time-Series Forecasting** (ARIMA) for demand prediction
- **ABC Categorization** to segment items by sales value impact
- **Supplier Performance Analysis** using lead time metrics
- **Monthly Sales Trends** and category-wise demand cycles

---

## ✅ Findings & Recommendations

- Overstock events dominate, indicating overly conservative ordering logic
- EOQ values suggest smaller, more frequent orders are optimal
- A-class SKUs (~44%) drive 80% of sales and need tighter control
- Most suppliers maintain consistent 9-day lead times; stockouts likely due to internal delays
- Seasonal trends suggest bulk purchases during year-end; dead stock risk in Q1

### Actionable Recommendations:
- Automate EOQ-based reorder logic
- Implement category-wise procurement rules
- Review suppliers based on service levels and delivery flexibility
- Use forecasting to align purchases with demand peaks

---

## 📈 Project Outcomes

- Expected reduction in inventory holding costs by **20%**
- Enhanced decision-making using data-backed policies
- Improved inventory turnover and availability of mission-critical SKUs
- Foundation set for scalable and resilient supply chain strategies within CSD

---





