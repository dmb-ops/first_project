# 📊 Amazon 2025 Sales Analysis

**Dataset:** Amazon Sales (250 transactions)  
**Tools:** Python · Pandas · Data Wrangling · Exploratory Data Analysis · Visualization

---

## 🧠 Project Objective

This project explores **sales performance patterns** in a 2025 Amazon dataset, focusing on:

- **Order status** (Completed, Cancelled, Pending)
- **Payment methods**
- **Customer location**
- **Product categories & pricing**

Our goal was to uncover actionable insights that drive **sales optimization**, **customer targeting**, and **inventory strategy**.

---

## 🔄 Data Preparation

We performed essential **data wrangling and cleaning**, including:

- Removing duplicates and irrelevant columns (`check_total`)
- Standardizing messy product names and date formats
- Creating new features like `Month` and `Year` for time-based analysis
- Verifying total sales values through a validation column

---

## 🔍 Hypotheses Explored

| Hypothesis ID | Focus Area             | Question                                                                 |
|---------------|------------------------|--------------------------------------------------------------------------|
| H1            | Payment Behavior       | Do certain payment methods lead to more cancellations?                   |
| H2            | Location Effect        | Do cities influence whether orders get completed or canceled?            |
| H3            | Category Performances  | Do electronics outperform other categories in total sales?               |
| H4            | Product Value          | Do high-priced products lead to more completed orders?                   |

---

## 📈 Key Findings

- 🧾 **Gift Cards** had the **lowest completion rate** among all payment methods.
- 🏙️ **Miami** showed an unexpectedly high number of completed orders.
- 💡 **Electronics**:
  - Accounted for **63% of completed sales**
  - Drove **47.2% of total revenue**
  - Had **high cancellation rates**, revealing volatility
- 🔌 **Home Appliances** performed strongly in completed sales, just behind Electronics.
- ⚠️ **Data integrity issue** discovered: `total_sales` mismatch — solved by introducing a `check_total` column.

---

## 🧪 Lessons Learned

- Always validate numeric fields and **challenge assumptions**.
- Clean, well-structured data leads to **faster, deeper insights**.
- Visual storytelling is key in translating analytical findings into business strategy.

---

## 💡 Business Recommendations

- 🎯 Prioritize Electronics in marketing and supply chain planning.
- 🛍️ Offer **discounts** and incentives for high-value categories.
- 🌍 Target cities with high completion trends (e.g., **Miami**).
- 📅 Schedule sales around months with highest historical sales.

---

## 📌 Next Steps

- Analyze customer-level behavior across time
- Run predictive modeling for cancellation likelihood
- Segment by seasonality and product lifecycle

---

## 👤 Team

**Damian Micó Bedoya**  
Data Analyst | SQL · Python · Tableau | Logistics & Business Intelligence  
📫 [dmico83@gmail.com](mailto:dmico83@gmail.com) | 📍 Barcelona, Spain  
🔗 [LinkedIn](#) | [GitHub](#)

---

> “Clean data, clear insights, smart business.”
