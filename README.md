# Infosys Financial Modeling & Valuation Analysis

This repository contains a comprehensive financial model and valuation analysis for **Infosys Ltd**. The primary asset is an in-depth Excel model projecting future performance, analyzing historical data, and determining intrinsic value using various valuation methodologies.

## 📂 Included Files

* **`Infosys.xlsx`**: The master spreadsheet containing all financial data, schedules, and valuation models. Please ensure macro settings and iterative calculations are enabled if modifying the circular references in the debt schedules.

## 📊 Model Structure & Key Components

The `Infosys.xlsx` workbook is organized into the following analytical tabs:

1. **Historical Financial Statement & Forecasts**
   * Historical income statements and balance sheets (2017–2026).
   * 5-year forward-looking projections (up to 2031) driving the core valuation models.

2. **Ratio & DuPont Analysis**
   * **Profitability Ratios:** Tracks Gross Profit Margin, EBITDA Margin, and EBIT Margin over the historical and projected periods.
   * **DuPont Model:** Breaks down Net Profit Margin, Asset Turnover, and Equity Multiplier to analyze Return on Equity (ROE) drivers (Tax Burden, Interest Burden, Operating Margin).

3. **BETA Calculation**
   * Regression analysis calculating Infosys's Beta against the **Nifty-500** index to determine systematic risk. Includes variance/covariance and correlation metrics.

4. **Discounted Cash Flow (DCF) Model**
   * Weighted Average Cost of Capital (WACC) calculation (Cost of Equity, Cost of Debt, Capital Structure weights).
   * Free Cash Flow to Firm (FCFF) projections using EBIT, D&A, and CapEx forecasts.
   * Terminal Value calculation and derivation of the implied share price.

5. **Comparable Company Analysis (COMPs)**
   * Relative valuation comparing Infosys against industry peers (e.g., **TCS** and **HCL Technologies**).
   * Analyzes multiples including EV/Revenue, EV/EBITDA, EV/EBIT, and P/E ratios.

6. **Common Size Statements**
   * Base-100 vertical analysis of the Income Statement and Balance Sheet to evaluate line items as a percentage of total sales/assets over time.

## 🚀 Getting Started

1. Clone or download this repository.
2. Open `Infosys.xlsx` in Microsoft Excel (version 2016 or newer recommended for optimal formula compatibility).
3. The **Data Sheet** and **Manual Data** tabs serve as the primary hardcoded input drivers. 
4. *Note: Avoid making manual changes to the projection cells, as they are formula-driven based on historical CAGR and margin assumptions.*

## ⚠️ Disclaimer

This financial model is provided for educational and informational purposes only. It does not constitute financial, investment, or trading advice. Past performance is not indicative of future results.
