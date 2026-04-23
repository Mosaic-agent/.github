# Mosaic Fund Agent

A personal AI-driven research tool for Indian retail investors to gain actionable investment insights.

**Project Repository:** [Mosaic-fund-agent](https://github.com/Mosaic-agent/Mosaic-fund-agent)

## Vision
To empower retail investors with institutional-grade analysis by combining live portfolio data, LLM-driven sentiment, risk scoring, and quantitative ML forecasting.

## The Problem We Are Solving
Addressing the challenge of fragmented financial data by centralizing holdings, news, and market signals into a single dashboard. It automates complex analyses (like ETF premium/discount tracking and volatility position sizing), freeing users from manual data engineering so they can make confident, data-driven decisions.

## Data Sources
*   **Portfolio:** Live holdings via Zerodha Kite MCP.
*   **Market:** Live ETF iNAV and prices from NSE.
*   **Commodities:** Pre-market signals via COMEX and Gold API.
*   **Institutional:** FII/DII cash and F&O participant OI data.
*   **News:** Global and local news from NewsAPI and GNews.
*   **Historical:** Mutual fund history for backtesting.

## Types of Data Handled
*   **Time-Series:** Historical price action and volatility stored in ClickHouse.
*   **Portfolio Metadata:** Sector breakdowns, holding weights, and risk scores.
*   **Unstructured Text:** News headlines processed by LLMs for sentiment.
*   **Quantitative Signals:** 25+ alpha features for LightGBM forecasting.
*   **Risk Metrics:** Regime detection and anomaly residuals.

## User Interface (UI)
*   **Streamlit Data Hub:** Web UI for data import, SQL exploration, and visual dashboards.
*   **Terminal/CLI:** Robust command-line interface with 13+ commands for analyzing portfolios, asking questions via LLM, and running imports.
*   **React Dashboard:** Auto-refreshing (every 5 minutes) React-based HTML dashboard generated from JSON reports for a quick overview of risk and sentiment.

## Key Features
- Live portfolio integration (Zerodha).
- LLM-driven sentiment analysis.
- Advanced risk scoring and GARCH-based anomaly detection.
- Dashboard for centralized insights.

## Getting Started

For detailed setup and installation instructions, please refer to the [Mosaic-fund-agent Repository](https://github.com/Mosaic-agent/Mosaic-fund-agent#getting-started).
