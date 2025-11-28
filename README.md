 
________________________________________

🌾📉 Agricultural Commodity Price Analysis & Market Insights (2024–2025)

________________________________________

🎯 1. Project Overview & Objective
             🔍 This project focuses on analysing agricultural commodity price fluctuations, market performance, and seasonality trends using Power BI.

             📌 The objective is to enable farmers, traders, and policymakers to take data-driven decisions based on price volatility, commodity stability, and regional insights.

🎯 Key Goals:

	📈 Identify stable vs. volatile commodities and markets
	📍 Determine top-performing districts & states based on pricing
	📅 Analyse season-wise & month-wise price patterns
	🏷 Support procurement, pricing & crop planning strategies

________________________________________

🗂️ 2. Data Sources

📊 Source	Details
🏛 Govt. & Market Data	Daily Commodity Market Prices
📆 Timeline	2024 – 2025
🌍 Domain	Agricultural Commodity & Market Analytics
________________________________________

❓ 3. Problem Statement

💡 To derive market and commodity intelligence that helps in:
	📉 Detecting price volatility and identifying stable commodities
	🏪 Studying district & market-level performance
	📆 Understanding seasonality pricing trends
	🧠 Supporting demand forecasting & profitable crop planning
________________________________________

📄 4. Attribute (Column / Features) Details

🔤 Field	🧾 Type	📌 Description
Commodity Name	Text	Crop/Commodity Name
Market Name	Text	Marketplace/District
Date	Date	Transaction Date
Modal Price	Numeric	Average Market Price
Min & Max Price	Numeric	Daily Price Range
Grade	Category	Premium / Local / Medium…
Season	Category	Monsoon / Winter / Autumn
________________________________________

🛠️ 5. Tools & Technologies

	📊 Power BI → Visual Analytics, DAX, Modelling
	📚 Power Query → Cleaning & Transformation
	🔢 DAX → Dynamic Insights & Measures
	🧠 Data Modelling → Star Schema with Fact & Dimensions
________________________________________

🧹 6. Data Pre-Processing Summary

	Removed invalid & null values
	Changed Date Type
	Standardized pricing formats
	Renamed Columns
	Created Calendar, Commodity & Market dimension tables
	 Feature Engineering (Volatility Index, Stability Score etc.)
________________________________________


🔗 7. Data Modelling & Key DAX

🧩 Star Schema Used

Fact Table (Daily Price)
  ↕
Commodity Dimension
Market Dimension
Calendar Dimension
Grade Dimension

📌 Important DAX Measures & Columns
Average Modal Price = AVERAGE ('Fact'[Model Price])
Stability Score = 1 / [Volatility Index]
Volatility Index = STDEV.P('Fact'[Model Price]) / AVERAGE ('Fact'[Model Price])
YTD Modal Price = TOTALYTD ([Average Model Price], 'Calendar'[Date])

📌 Important Calculated tables
	Calander Table
	Measures Table

________________________________________

📊 8. Analysis & Visual Insights

📦 Dashboard 1 – Commodity Analysis

🔹 Top Stable Commodities
           🥇 Bitter Gourd (99.52) | 🥈 Mint (71.18) | 🥉 Ash gourd (67.22)

🔹 Commodity Grade Preference
       🏆 Premium: 76.6% (755 records) → Highly demanded
         📍 Local: 105, Medium & Non-Premium minimal

🔹 Volatility Trend
           📉 Bitter Gourd (Low volatility) → Highly reliable
           📈 Some vegetables show high fluctuation

🔹 Min Price By Commodity
        🥇 Bitter Gourd ₹2.2K | Mint ₹2.1K | Amaranthus ₹2K

🔹 District-Wise Max Price

🌾 Commodity	🏙 District	💵 Max Price
Carrot Alappuzha	₹2350
Ash gourd	Palakkad	₹1600
Brinjal	Nagpur	₹1820

________________________________________

🏪 Dashboard 2 – Market Analysis

🔹 Top Stable Markets

🏆 Rank	Market	Stability
🥇 1	Surat	48.92
🥈 2	Rampur	42.78
🥉 3	Godhra	33.41

🔹 State Wise Average Min Price
	🔝 Tamil Nadu (11.48%) | Himachal (10.61%) | Rajasthan (10.12%)

🔹 State-Wise YTD Price
	📈 Punjab: ₹0.3M | Haryana: ₹0.2M | Gujarat: ₹0.2M

🔹 High Price Markets
	Surat ₹121K | Rampur ₹98K | Godhra ₹80K
________________________________________

📅 Dashboard 3 – Calendar Analysis

🔹 Month-Wise Average Model Price

	📈 September highest – ₹1.76K
	📉 January–August stable (~₹1.51K)

🔹 Season Wise Max Price

	🌧 Monsoon & Winter peak
	🍂 Autumn slightly lower

🔹 State Wise Volatility (By Seas
on)

State	📉 Volatility Index
Maharashtra	99.41 😬 (High Risk)
Kerala	-8.12
Punjab	-5.22

🔹 Grade Wise Price Contribution

	⭐ Premium → 62.16%
	Medium & Local → Moderate

________________________________________

💡 9. Insights (Business & Strategy)

📊 Descriptive
✔ Bitter gourd is most stable & high-priced
✔ Surat & Rampur are best-selling markets

🔍 Diagnostic
⚠ Maharashtra shows extreme volatility, requiring risk measures
⚠ Seasonal price variation impacts profitability

🔮 Predictive
📈 Monsoon & Winter expected to remain high revenue seasons
📌 Premium grade likely to dominate next cycle

📝 Prescriptive
🛒 Promote Premium grade trading
📍 Expand distribution in Surat, Rampur, Godhra
🌱 Grow low volatility commodities like Bitter Gourd, Mint
🛑 Avoid heavy supply during highly volatile months

________________________________________

🔚 10. Conclusion
✔ Successfully developed an end-to-end Power BI solution
✔ Enabled clear identification of profitable commodities, markets & seasons
✔ Empowered decision-makers with risk-based strategies
✔ Integration of seasonality, price, and volatility metrics is a unique highlight
 
---

## 🤝 Contribution & Feedback

Contributions are welcome!
Create a PR or reach out via LinkedIn for suggestions.

---

## 📬 Author

👤 **M. Punitha**

Aspiring Data Analyst

📧 Email: (punithagvgvc@gmail.com)

🔗 LinkedIn: (www.linkedin.com/in/punitha-muthusamy-6b46b2244)

🐙 GitHub: (https://github.com/punithamuthusamy-ux)

---

⭐ *If you found this useful, consider starring the repo!*
📢 *Let’s empower agriculture through data analytics!*

---

