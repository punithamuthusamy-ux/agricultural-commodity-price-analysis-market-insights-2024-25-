 
# 🌾📉 Agricultural Commodity Price Analysis & Market Insights (2024–2025)

A **Power BI Dashboard** designed to evaluate **agricultural commodity pricing trends, market performance, seasonality analysis, and volatility-based risk assessment** to support decision-making for **farmers, traders & policymakers.**

---

## 🎯 1. Project Overview & Objective

🔍 This project focuses on analysing **agricultural commodity price fluctuations, market performance, and seasonality trends using Power BI.**

📌 The objective is to enable **farmers, traders, and policymakers** to take **data-driven decisions** based on:
- Price volatility  
- Commodity stability  
- Regional insights  

### 🎯 Key Goals:

- 📈 Identify **stable vs. volatile commodities and markets**
- 📍 Determine **top-performing districts & states** based on pricing
- 📅 Analyse **season-wise & month-wise price patterns**
- 🏷 Support **procurement, pricing & crop planning strategies**

---

## 🗂️ 2. Data Sources

| 📊 Source | Details |
|-----------|----------|
| 🏛 Govt.Data | Daily Commodity Market Prices |
| 📆 Timeline | 2024 – 2025 |
| 🌍 Domain | Agricultural Commodity & Market Analytics |

---

## ❓ 3. Problem Statement

💡 To derive **market and commodity intelligence** that helps in:
- 📉 Detecting price volatility & identifying **stable commodities**
- 🏪 Studying **district & market-level performance**
- 📆 Understanding **seasonality pricing trends**
- 🧠 Supporting **demand forecasting & profitable crop planning**

---

## 📄 4. Attribute (Column / Features) Details

| 🔤 Field | 🧾 Type | 📌 Description |
|----------|----------|----------------|
| Commodity Name | Text | Crop/Commodity Name |
| Market Name | Text | Marketplace/District |
| Date | Date | Transaction Date |
| Modal Price | Numeric | Average Market Price |
| Min & Max Price | Numeric | Daily Price Range |
| Grade | Category | Premium / Local / Medium |
| Season | Category | Monsoon / Winter / Autumn |

---

## 🛠️ 5. Tools & Technologies

- 📊 **Power BI** → Visual Analytics, Dashboards, DAX  
- 📚 **Power Query** → Data Cleaning & Transformation  
- 🔢 **DAX** → Measures & KPI Calculations  
- 🧠 **Data Modelling** → Star Schema (Fact & Dimensions)

---

## 🧹 6. Data Pre-Processing Summary

✔ Removed invalid & null values  
✔ Changed date format to Date type  
✔ Standardized pricing formats  
✔ Renamed columns for consistency  
✔ Created **Calendar, Commodity & Market** dimension tables  
✔ Engineered metrics like **Volatility Index, Stability Score**

---

## 🔗 7. Data Modelling & Key DAX

### 🧩 Star Schema

Fact Table (Daily Price)
    
              ↕
              
* Commodity Dimension 

* Market Dimension 

* Calendar Dimension 

*  Grade Dimension

###📌 Important DAX Measures & Columns

Average Modal Price = AVERAGE('Fact'[Model Price])

Volatility Index = STDEV.P('Fact'[Model Price]) / AVERAGE('Fact'[Model Price])

Stability Score = 1 / [Volatility Index]

YTD Modal Price = TOTALYTD([Average Model Price], 'Calendar'[Date])

### 📌 Important Calculated Tables

* ➤ Calendar Table
* ➤ Measures Table

---

## 📊 8. Analysis & Visual Insights

### 📦 Dashboard 1 – Commodity Analysis

* 🥇 **Top Stable Commodities:** Bitter Gourd (99.52), Mint (71.18), Ash Gourd (67.22)
* 🏆 **Grade Preference:** Premium – 76.6% (755 records)
* 📉 Low Volatility: Bitter Gourd → Highly reliable
* 💰 **Min Price:** Bitter Gourd ₹2.2K | Mint ₹2.1K | Amaranthus ₹2K
* 🌾 **District-Wise Max Price:**

| Commodity | District  | 💵 Max Price |
| --------- | --------- | ------------ |
| Carrot    | Alappuzha | ₹2350        |
| Ash Gourd | Palakkad  | ₹1600        |
| Brinjal   | Nagpur    | ₹1820        |

---

### 🏪 Dashboard 2 – Market Analysis

| 🏆 Rank | Market | Stability Score |
| ------- | ------ | --------------- |
| 🥇 1    | Surat  | 48.92           |
| 🥈 2    | Rampur | 42.78           |
| 🥉 3    | Godhra | 33.41           |

📌 Additional Insights:

* 🔝 **State-wise Avg Min Price:** Tamil Nadu (11.48%) | Himachal (10.61%) | Rajasthan (10.12%)
* 📈 **YTD Price:** Punjab ₹0.3M | Haryana ₹0.2M | Gujarat ₹0.2M
* 💹 **Top Markets by Price:** Surat ₹121K | Rampur ₹98K | Godhra ₹80K

---

### 📅 Dashboard 3 – Calendar Insights

* 📈 **September highest Avg Model Price – ₹1.76K**
* 🗓 **Jan–Aug stable (~₹1.51K)**
* 🌧 **Monsoon & Winter show peak prices**
* 🍂 Autumn slightly lower
* ⚠ **Most Volatile State:** Maharashtra (99.41)

| State       | 📉 Volatility Index | 🔎 Risk |
| ----------- | ------------------- | ------- |
| Maharashtra | 99.41               | 😬 High |
| Kerala      | -8.12               | Low     |
| Punjab      | -5.22               | Low     |

⭐ **Price Contribution by Grade:** Premium → **62.16%**

---

## 💡 9. Insights (Business & Strategy)

### 📊 Descriptive

✔ Bitter Gourd is most stable & high-priced
✔ Surat & Rampur are top-performing markets

### 🔍 Diagnostic

⚠ Maharashtra exhibits **high volatility**
⚠ Seasonal price variation impacts profitability

### 🔮 Predictive

📈 Monsoon & Winter expected to sustain high price trends
📌 Premium grade likely to dominate

### 📝 Prescriptive

* 🛒 Promote **Premium Grade** trading
* 📍 Expand distribution in **Surat, Rampur, Godhra**
* 🌱 Focus on **low volatility commodities** (Bitter Gourd, Mint)
* 🚫 Avoid over-supply in highly volatile months

---

## 🔚 10. Conclusion

✔ Developed a complete **Power BI analytical solution**
✔ Identified **profitable commodities, markets & seasons**
✔ Enabled **data-driven agricultural decisions**
✔ Highlighted **seasonality & volatility in pricing models**

---

## 🤝 Contribution & Feedback

Contributions are welcome!
📌 Feel free to create a pull request or share suggestions on LinkedIn!

---

## 📬 Author

👤 **M. Punitha**
💼 *Aspiring Data Analyst*
📧 **Email:**   *[punithagvgvc@gmail.com](mailto:punithagvgvc@gmail.com)*
🔗 **LinkedIn:** [www.linkedin.com/in/punitha-muthusamy-6b46b2244](http://www.linkedin.com/in/punitha-muthusamy-6b46b2244)
🐙 **GitHub:** github.com/punithamuthusamy-ux

---

⭐ *If you found this useful, don't forget to star the repository!*
📢 *Let’s empower agriculture through data analytics!* 🌾📊🚀

```
 
