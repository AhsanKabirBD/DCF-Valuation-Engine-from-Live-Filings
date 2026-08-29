# DCF-Valuation-Engine-from-Live-Filings
Pulls real financial statement data for any US-listed ticker, projects free cash flow, discounts it at WACC, and outputs an intrinsic value per share — with a WACC × terminal-growth sensitivity table.

Data source: Yahoo Finance via yfinance (fast, reliable financials + market data). SEC EDGAR is included as a secondary/cross-check source for raw XBRL filing data — useful if you want to verify a line item straight from the 10-K instead of trusting an aggregator.

How to use this notebook: change TICKER in the Setup cell, run all cells top to bottom, and read the output at the bottom. Every assumption (growth rates, margins, WACC inputs) lives in one clearly marked cell so you can stress-test your own view instead of trusting the defaults.
