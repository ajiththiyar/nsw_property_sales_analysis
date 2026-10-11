# 🏡 NSW Property Market Investment & Growth Analytics

**Role:** Business Analyst  

An analysis of over 1.5 million NSW property sales, turned into a simple interactive dashboard that shows investors **where to invest in New South Wales**.

🔗 **[View the Live Tableau Dashboard](https://public.tableau.com/app/profile/ajith.attikkachalil/viz/nsw_property_sales_dashboard/MainDashBoard?publish=yes)**  
🗄️ **[Dataset: NSW Property Sales Data](https://nswpropertysalesdata.com/)**

---

## 📌 Business Requirement

Real estate investors and portfolio managers needed clear, data-backed answers on **where to put their money in NSW**. The raw sales data was messy and unreliable, so it was hard to compare locations on:
- How fast property values are growing
- How much buyers pay per square metre
- Which property types perform best (homes, commercial, industrial, vacant land, car spaces)

## 🎯 Task Overview

Turn 1.5 million raw property sales into a clean, decision-ready tool by:
- Cleaning the data so only genuine, fair-market sales remain
- Analysing price growth, price per square metre and property types across NSW
- Building an interactive dashboard that lets decision-makers explore suburbs and drill down to individual addresses
- Providing clear investment recommendations

## ⚙️ Action

- **Cleaned the data:** Removed family transfers, part-ownership sales and unrealistic prices, fixed errors in dates, postcodes and council names, and filled in missing land sizes. From about 1.5 million records, **1,121,519 reliable sales** remained.
- **Stored it in a database:** Loaded the clean data into a database so it can be queried quickly.
- **Analysed the market:** Looked at price trends over time, prices by council, suburb and postcode, performance by property type, and how much individual properties rose in value between repeat sales.
- **Built the dashboard:** An interactive Tableau dashboard with:
  - **Headline numbers** for price change, price per square metre and total sales
  - **A map of NSW** showing where prices and growth are highest
  - **A trend chart** of price per square metre from 2019 to 2026
  - **A suburb ranking** by growth or value
  - **A 4-box opportunity chart** that sorts every suburb into one of four groups, including **"High Growth, Still Affordable"**
  - **Address-level drill-down** so clients can click a suburb and see individual properties to follow up on

## 📈 Business Recommendation

- **Systematic Quadrant 1 Target Acquisition ("High Growth, Still Affordable"):** Prioritize capital deployment into postcodes categorized under Quadrant 1 in the Tableau model (suburbs where median capital growth exceeds the NSW state average, yet median price per square metre remains below state averages) to secure high upside prior to market repricing.
- **Outer-Ring Infrastructure Corridor Expansion:** Focus acquisitions along expanding outer-ring corridors adjacent to major catalysts like the Western Sydney International Airport (Badgerys Creek corridor) before full operational activation.
- **Cash-Flow Hedging via High-Yield Niche Assets:** Incorporate high-density commercial parking spaces into the portfolio mix to leverage their high price-per-square-metre yield as a cash-flow buffer against landholding costs.
- **Multi-LGA Risk-Adjusted Portfolio Hedging:** Balance allocations across high-growth infrastructure corridors and stable, high-median Council Local Government Areas (LGAs) to hedge against localized market shifts.

---

## 🧰 Tech Stack
`Python` `Pandas` `Docker` `Azure SQL Edge` `T-SQL` `Tableau`
