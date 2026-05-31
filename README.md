# pension-etf-quant-pipeline

An automated, data-driven investment pipeline optimized for Defined Contribution (DC) retirement accounts, utilizing combined technical indicators and a Core-Satellite asset allocation strategy.

## Key Features
- **Dual-Indicator Signal Engine**: Generates execution signals by combining the Relative Strength Index (RSI) and Moving Average Divergence to minimize whipsaws and identify structural turning points.
- **Core-Satellite Portfolio Optimization**: Systematically manages core assets (long-term stability) and satellite assets (tactical alpha tracking) to maximize risk-adjusted returns within pension account constraints.
- **Cross-Platform Automation Pipeline**: Seamlessly integrates Python-based quantitative engines with Google Apps Script (GAS) for cloud-based data logging and Telegram API for real-time rebalancing alerts.

## Architecture & Workflow
1. **Data Ingestion**: Fetching financial market data via Google Sheets and automated data scraping.
2. **Signal Generation**: Evaluating technical setups based on the integrated RSI and divergence logic.
3. **Portfolio Rebalancing**: Computing tactical weights between core and satellite assets based on calculated matrix.
4. **Alerting System**: Dispatching instantaneous, actionable execution alerts to the operator via Telegram.

## Getting Started
Ensure you have the required dependencies installed:

`pip install -r requirements.txt`
