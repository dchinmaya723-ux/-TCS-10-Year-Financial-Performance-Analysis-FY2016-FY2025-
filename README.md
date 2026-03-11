# 📊 TCS — 10-Year Financial Performance Analysis (FY2016–FY2025)

> A comprehensive Excel-based financial model for **Tata Consultancy Services Ltd (TCS)**, covering a decade of historical performance, ratio analysis, forecasting, WACC computation, and an interactive KPI dashboard.

---

## 🏢 About the Project

This project is a structured financial analysis workbook built entirely in Microsoft Excel. It covers TCS's financial performance from **FY2016 to FY2025**, with quarterly data, forecast projections, and peer benchmarking — giving investors, analysts, and students a full-picture view of one of India's largest IT companies.

**Key FY2025 Highlights modelled in this workbook:**

| Metric | Value |
|---|---|
| Revenue | ₹2,55,324 Cr (+6.0% YoY) |
| Net Profit | ₹48,553 Cr (+5.8% YoY) |
| EBITDA Margin | 27.86% (10-Yr Avg: 29.4%) |
| Return on Equity | 47.32% (10-Yr Avg: 35.7%) |
| Cash from Operations | ₹48,908 Cr (+10.3% YoY) |

---

## 📁 Workbook Structure

The file `TCS.xlsx` contains **9 interconnected sheets**, each serving a distinct analytical purpose:

### 1. `Dashboard`
A high-level visual summary of TCS's 10-year performance (FY2016–FY2025). Displays key headline metrics including Revenue, Net Profit, EBITDA Margin, ROE, and Operating Cash Flow with YoY comparisons — designed as a single-glance executive view.

### 2. `KPI`
A dynamic KPI tracker that compares FY25 actuals against preset targets. Each metric is automatically flagged as:
- ✅ On Target
- 🟡 Near Target
- 🔴 Off Target

Tracks Revenue, Net Profit, EBITDA, Operating Cash Flow, Net Profit Margin, EBITDA Margin, ROE, and ROCE.

### 3. `HistoricalFS`
The core financial statements spanning FY2016 to FY2025 (LTM included), pulled dynamically from the `Data Sheet`. Contains:
- Full **Income Statement** (Sales, COGS, EBITDA, EBIT, PBT, Net Profit)
- Full **Balance Sheet** (Assets, Equity, Borrowings, Liabilities)
- Full **Cash Flow Statement** (Operating, Investing, Financing)

### 4. `Ratio Analysis`
A comprehensive ratio analysis sheet with **trend, mean, and median** columns for every metric across 10 years. Covers:
- **Growth Ratios:** Sales, EBITDA, EBIT, Net Profit, Dividend
- **Profitability Margins:** Gross, EBITDA, EBIT, EBT, Net Profit
- **Return Metrics:** ROCE, ROE, Self-Sustained Growth Rate
- **Efficiency Ratios:** Debtor/Creditor/Inventory Turnover, Fixed Asset & Capital Turnover
- **Working Capital (Days):** Debtor Days, Payable Days, Inventory Days, Cash Conversion Cycle
- **Cash Flow Ratios:** CFO/Sales, CFO/Total Assets, CFO/Total Debt

### 5. `Forecasting`
Forward-looking projections for three key financial metrics using historical trend regression:
- **Sales Forecasting** (with YoY growth rates)
- **EBITDA Forecasting** (with YoY growth rates)
- **EPS Forecasting** (with YoY growth rates)

### 6. `WACC`
Weighted Average Cost of Capital computation including:
- **Peer benchmarking** against Infosys, Wipro, HCL Tech, and LT Mindtree
- Levered and Unlevered Beta calculations
- Debt/Equity capital structure breakdown
- Pre-tax and post-tax cost of debt
- Notes on methodology (marginal tax rate, 5-year monthly beta)

### 7. `Data Sheet`
The master raw data input sheet — **do not modify**. Contains:
- Annual P&L data (FY2016–FY2025)
- Quarterly P&L data (last 4 quarters)
- Balance Sheet data
- Cash Flow data
- Stock price history and market capitalisation
- Meta information (Face Value, Current Price, Shares Outstanding)

### 8. `Common Size Statement`
A vertically common-sized Income Statement, expressing every line item as a percentage of Sales across all 10 years — useful for trend spotting and margin analysis.

### 9. `Cash Flow Data`
Detailed breakdown of operating cash flow components across FY2016–FY2025:
- Cash from Operating / Investing / Financing Activities
- Working capital changes (Receivables, Payables, Inventory)
- Profit from operations

---

## 🛠️ How to Use

1. **Download** `TCS.xlsx` and open in Microsoft Excel (2016 or later recommended).
2. **Do not edit** the `Data Sheet` — all other sheets pull data from it via formulas.
3. To update for a new financial year, add a new column to `Data Sheet` with the latest Annual P&L, Balance Sheet, and Cash Flow figures.
4. All KPIs, ratios, charts, and forecasts will **auto-refresh** upon data entry.
5. Use the `Dashboard` tab for a quick executive summary.

---

## 📐 Technical Details

- **Tool:** Microsoft Excel (.xlsx), Version 2.1
- **Formula Types:** Dynamic cross-sheet references, `IFERROR`, `IF`, `AVERAGE`, `MEDIAN`, `SUM`, array formulas
- **Charts:** Multiple embedded charts (revenue trend, margin trend, ratio charts)
- **Version Check:** The workbook includes a built-in version check that alerts if the sheet template is outdated

---

## 📌 Company Overview

| Field | Details |
|---|---|
| Company | Tata Consultancy Services Ltd |
| Sector | Information Technology |
| Listed On | BSE / NSE (India) |
| Face Value | ₹1 per share |
| Analysis Period | FY2016 – FY2025 |

---

## ⚠️ Disclaimer

This workbook is intended for **educational and research purposes only**. The data is sourced from publicly available financial statements. This does not constitute financial advice. Always verify figures against official filings before making investment decisions.

---

## 🙌 Acknowledgements

Financial data sourced from TCS's publicly available Annual Reports and screener/financial data platforms. Peer comparison data includes Infosys, Wipro, HCL Technologies, and LT Mindtree.
