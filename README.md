# 🌍 Global Housing Market Power BI Dashboard

## 📊 Project Overview
The **Global Housing Market Dashboard** provides a comprehensive analysis of worldwide housing trends — tracking **House Price Index, Rent Index, Rental Yield, Mortgage Rate,** and **GDP Growth** across multiple countries.  
It highlights global affordability patterns, rental return potential, and economic strength at a glance.

---

![📊 Dashboard Preview](https://github.com/yourusername/global-housing-market-dashboard/blob/main/dashboard.png)

---

## 🧰 Tools & Technologies
- **Power BI Desktop** – Interactive data visualization  
- **Microsoft Excel / CSV** – Data source  
- **DAX (Data Analysis Expressions)** – KPI calculations  
- **Power Query** – Data transformation and cleaning  
- **GitHub** – Version control and project sharing  

---

## 🗂️ Dataset Information
**Dataset Name:** `global_housing_market_extended`  
**Source:** Open-source global housing dataset (country-level indicators)  
**Key Columns:**  
- `Country`  
- `Year`  
- `House_Price_Index`  
- `Rent_Index`  
- `Mortgage_Rate`  
- `GDP_Growth`

---

## 🧮 Key Performance Indicators (KPIs)

| KPI | Measure | Description |
|-----|----------|-------------|
| 🏠 **Avg House Price Index** | `AVERAGE(global_housing_market_extended[House_Price_Index])` | Shows average housing price level |
| 💰 **Avg Rent Index** | `AVERAGE(global_housing_market_extended[Rent_Index])` | Represents average rental value |
| 📈 **Avg Rental Yield (%)** | `(AVERAGE(global_housing_market_extended[Rent_Index])*12 / AVERAGE(global_housing_market_extended[House_Price_Index])) * 100` | Measures annual rental return |
| 📉 **Avg Mortgage Rate (%)** | `AVERAGE(global_housing_market_extended[Mortgage_Rate])` | Reflects average loan interest rates |
| 💹 **Avg GDP Growth (%)** | `AVERAGE(global_housing_market_extended[GDP_Growth])` | Indicates overall economic strength |

---

## 📌 Analytical Highlights

1. **Global Housing Surge:**  
   Many developed nations experienced a steady rise in the **House Price Index** over the last decade, signaling reduced affordability.

2. **Emerging Market Opportunities:**  
   Countries with **high rental yields (above 5%)** suggest promising returns for real estate investors.

3. **Interest Rate Trends:**  
   The **Mortgage Rate** remained stable in most regions post-pandemic, while a few economies showed sharp hikes tied to inflation.

4. **GDP–Housing Correlation:**  
   A positive correlation between **GDP Growth** and **House Price Index** indicates that strong economies sustain healthy real estate demand.

5. **Regional Insights:**  
   - Europe and North America show mature but expensive markets.  
   - South Asia and parts of Africa reveal affordable yet growing investment zones.  

---

## 💡 Key Insights Summary
- 🏡 **Housing prices** continue to grow globally, outpacing income levels.  
- 💵 **Rental yields** remain strong in developing economies, driving investor focus.  
- 📉 **Low mortgage rates** fueled price booms in 2020–2023 but are now stabilizing.  
- 🌐 **Economic growth** remains a major driver of housing demand and pricing stability.  

---

## 🧭 Project Objective
To deliver a **one-page Power BI dashboard** offering fast, comparative insights into global real estate dynamics and investment feasibility.

---

## 🏁 Conclusion
This Power BI dashboard summarizes the **core indicators shaping the global housing landscape** — connecting real estate, rent dynamics, mortgage behavior, and macroeconomic strength into one unified visual experience.


