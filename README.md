Project Title

Trader Performance Analysis vs Bitcoin Market Sentiment

Overview

This project explores how Bitcoin market sentiment influences trading behavior and profitability.
By combining the Fear and Greed Index with historical Hyperliquid trading data, the goal is to uncover patterns that can support strategic trading decisions regarding leverage usage, risk management, and timing in volatile conditions.

Directory Structure
ds_<sripriya>/
├── notebook_1.ipynb      # Main Google Colab analysis notebook
├     
├── csv_files/            # All raw and processed data storage
│   ├── historical_data.csv
│   └── fear_greed_index.csv
├── outputs/              # Exported visualizations and charts
│   └── *.png / *.jpg
├── ds_report.pdf         # Final summarized results and insights
└── README.md             # Project documentation

Data Sources

Bitcoin Fear and Greed Index
Columns: timestamp, value, classification, date

Hyperliquid Trader Execution Data
Columns include: account, symbol, execution price, size, side, timestamp, start position, closed PnL, leverage information (if applicable), etc.

Objectives

Parse and clean sentiment and trader datasets

Convert timestamps into a unified format for accurate merging

Perform EDA to understand trader behavior in various sentiment phases

Analyze correlation between:

Sentiment and profitability

Leverage usage and risk exposure

Visualize outcomes clearly through charts and heatmaps

Tools and Technologies

Python (pandas, numpy, seaborn, matplotlib)

Google Colab

ReportLab for PDF generation

Key Insights

High leverage under Fear sentiment generally results in increased losses

Greed phases show mixed profitability, often linked to increased volatility

Neutral sentiment environments may offer more stable profit opportunities

Market psychology has measurable influence on trader performance

How to Run

Upload CSV files in the csv_files folder to Google Colab

Execute cells in notebook_1.ipynb

Visual results will be saved into the outputs directory

The final report (ds_report.pdf) is automatically generated

Deliverables

Complete data analysis and code in notebook

Exported visual findings (heatmaps, performance charts)

Final summary in PDF format