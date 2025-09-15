# 📊 Equity Research Dashboard – IT Sector (Power BI + Power Query + Python Scripting)

An interactive **Equity Research Dashboard** built in **Power BI** analyzing top Indian IT companies – **TCS, Infosys, Wipro, HCL Tech, and Tech Mahindra**.  
The project integrates **financial statement analysis, valuation multiples, profitability ratios, and market performance trends**.  
It also includes a **Python data pipeline** to automate stock price data extraction from Yahoo Finance (2018–2025).

---

## 🔑 Key Features

- **Market Capitalization Analysis**  
  Treemap visualization showing company size relative to peers.

- **Valuation Multiples**  
  P/E Ratio & Forward P/E comparison across companies.

- **Profitability Ratios**  
  Net Margin, ROE, ROA visualized across competitors.

- **Revenue Mix**  
  Pie chart of revenue distribution by company.

- **Stock Price Performance**  
  Line chart of historical market prices (2018–2025).

- **Automated Data Pipeline**  
  Python script (`yfinance`) to download daily stock data, clean & export to Excel/CSV for Power BI.

---
## Preview of the Financial Analytics Dashboard
- **Company Overview**
- https://github.com/pradyumaann/Equity_Research_Dashboard/blob/main/Dashboard%3A%201%20-%3E%20Company%20Overview.png
- **Company Comparable Analysis**
- https://github.com/pradyumaann/Equity_Research_Dashboard/blob/main/Dashboard%3A%202%20-%3E%20Company%20Comparable%20Analysis.png
- **P&L Analysis**
- https://github.com/pradyumaann/Equity_Research_Dashboard/blob/main/Dashboard%3A%203%20-%3E%20P%26L%20Analysis.png
- **Balance Sheet Analysis**
- https://github.com/pradyumaann/Equity_Research_Dashboard/blob/main/Dashboard%3A%204%20-%3E%20Balance%20Sheet%20Analysis.png
- **Cash Flow Analysis**
- https://github.com/pradyumaann/Equity_Research_Dashboard/blob/main/Dashboard%3A%205%20-%3E%20Cash%20Flow%20Analysis.png


## 🛠️ Tech Stack

- **Power BI Desktop**
  - DAX Measures for KPIs (YoY Growth, Asset Growth, Profitability Ratios, Cash Flow Ratios, Valuation Multiples)
  - Interactive visuals (Treemap, Bar, Pie, Line, Clustered Column Charts)

- **Python**
  - `yfinance` → Stock data download (2018–2025)  
  - `pandas` → Data cleaning & transformation  
  - `openpyxl` → Export to Excel for Power BI integration  

- **Excel/CSV** → Data staging before Power BI load

---

## 🚀 Project Workflow

1. **Data Acquisition (Python)**
   - Download daily stock data for TCS, Infosys, Wipro, HCL Tech, Tech Mahindra.  
   - Save close prices (2018–2025) into Excel (`IT_Stocks_2018_2025.xlsx`).  

2. **Data Modeling (Power BI)**
   - Load Balance Sheet, P&L, and Cash Flow datasets.  
   - Create relationships between tables.  
   - Add DAX measures for key ratios:  
     - Profitability → Net Margin, ROE, ROA  
     - Liquidity → Current Ratio, Quick Ratio  
     - Valuation → P/E, Forward P/E  
     - Cash Flow → OCF Ratio, Cash Flow to Debt, FCF, Cash Flow Margin  

3. **Visualization (Dashboard)**
   - Market Cap Treemap  
   - Revenue Pie Chart  
   - Valuation Multiples Bar Chart  
   - Profitability Ratios Column Chart  
   - Stock Price Trend (2018–2025)  

---


