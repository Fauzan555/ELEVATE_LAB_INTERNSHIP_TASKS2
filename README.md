# 🛍️ Superstore Sales Data Analysis & Visualization

## 🔍 Project Overview

This project focuses on performing **exploratory data analysis (EDA)** and **business intelligence visualizations** using the **Sample Superstore dataset**. The goal is to uncover actionable insights related to **sales, profit, customer behavior, product categories**, and **logistics performance**.

---

## 📁 Dataset

- **Source**: [Sample - Superstore.csv]
- **Rows**: ~10,000+
- **Columns**: 21 features including:
  - `Order Date`, `Ship Date`
  - `Sales`, `Profit`, `Discount`, `Quantity`
  - `Category`, `Sub-Category`
  - `Customer Name`, `State`, `Region`, `Segment`
  - `Ship Mode`, etc.

---

## ⚙️ Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Jupyter Notebook**

---

## 📊 Key Visual Analyses & Insights

| Analysis Area | Description |
|---------------|-------------|
| 📈 **Sales & Profit Over Time** | Volatility in sales with weak correlation to profit highlights pricing/margin issues. |
| 🧾 **Category & Sub-Category Analysis** | Some sub-categories (e.g., Tables, Bookcases) consistently produce **losses**. |
| 💸 **Discount vs Profit** | High discounts often lead to negative profits; discount strategy needs revision. |
| 🧭 **Region & State-level Sales** | Western and Eastern regions outperform others in terms of sales volume. |
| 🚛 **Shipping Mode** | Standard Class dominates, but analysis reveals possible delays in shipment. |
| 🧑‍💼 **Top Customers & Products** | Identified most loyal and high-spending customers and best/worst selling products. |
| ⏱️ **Delivery & Processing Time** | Average delivery time calculated; delays observed in certain states. |

---

## 📌 Business Recommendations

- **Reassess Discounting Strategy**: Especially for unprofitable categories like Tables, Machines.
- **Focus on High-Margin Segments**: Segment-wise profitability can guide sales targeting.
- **Improve Logistics**: Analyze delays by ship mode and state to enhance delivery.
- **Product Optimization**: Discontinue or bundle loss-making products with better-performing ones.

---

## 📎 File Structure

```
├── Task2_Data_Visualization.ipynb     # Complete EDA and visualization code
├── Sample - Superstore.csv            # Dataset (optional for GitHub upload)
├── README.md                          # Project documentation
```

---

## 💼 Ideal for

- **Business Intelligence (BI) Projects**
- **Data Analyst Portfolio**
- **Pre-sales analytics use cases**
- **Retail Optimization Case Studies**
