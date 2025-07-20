# Riskified Fraud Detection Analysis

This project focuses on analyzing e-commerce transaction data to identify **patterns in fraud (chargebacks)** and **optimize the approval threshold** for online orders. The analysis was designed to simulate a fraud detection use case similar to how **Riskified** might approach approval decisions for digital and tangible products.

---

##  Objective

- Find the **optimal classification threshold** that approves 90% of orders while minimizing chargebacks.
- Compare the fraud behavior across **digital vs. tangible goods**.
- Explore key patterns in **customer behavior, order value, and account age** that influence chargeback likelihood.
- Recommend data-driven actions for fraud prevention and approval logic.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Visualization
- **Jupyter Notebook** – Interactive EDA

---

## Key Insights

- ✅ A **threshold score** was identified to approve 90% of orders safely.
- 📉 **Customer Account Age** is negatively correlated with chargeback risk — newer accounts are riskier.
- 💰 Almost all charged-back orders are concentrated below a certain **order_price** (~₹1500).
- 🧾 **Digital goods** have different fraud patterns than tangible ones, with generally higher chargeback ratios.
  
---

## Sample Visual Analysis

- Distribution plots comparing **approved vs. chargeback orders**
- Count plots for **product type vs. fraud**
- Trendlines showing how fraud correlates with **order price and customer age**

---

## Dataset

- A sample dataset (`Technical Interview Dataset.xlsx`) was used with anonymized fields such as:
  - `order_price`
  - `classification_score`
  - `product_type`
  - `customer_account_age`
  - `label` (approved/chargeback)

---

## Outcome

The project resulted in a **threshold-based logic** that could help a fraud detection engine improve its **approval accuracy** while minimizing business losses due to chargebacks. It also recommended **fee adjustments** or stricter screening for:
- Orders from **new customers**
- Orders below a **price threshold**
- Certain **product categories (digital)**

---

## Contact

Made by **Anshul Jain**  
jainanshul387@gmail.com
Thank You
